A deep learning CNN imaging classifier that differentiates between Clean and Polluted Water
# Polluted vs. Clean Water Classifier

## Overview
This project implements a **Deep CNN Image Classifier** to differentiate between polluted and clean water images. Developed using **TensorFlow** and **Keras**, the model achieves an accuracy of **93%**, utilizing a robust pipeline for data preprocessing, training, and evaluation.

---

## Features
- **Data Preprocessing**: Includes image validation and normalization using `OpenCV`, `os`, and `imghdr`.
- **Deep Learning Architecture**:
  - A Convolutional Neural Network (CNN) with:
    - 3 convolutional layers (`Conv2D`) and max-pooling layers.
    - A dense layer with **ReLU activation** for feature extraction.
    - Final **sigmoid activation** for binary classification.
- **Training Workflow**:
  - Dataset split into 70% training, 20% validation, and 10% testing.
  - Data normalization for improved model performance.

---

## Installation

### Dependencies
Install the required libraries:
```bash
pip install tensorflow opencv-python matplotlib

