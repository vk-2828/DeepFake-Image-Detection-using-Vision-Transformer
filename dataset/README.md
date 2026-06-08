# DeepFake Image Detection using Vision Transformer

## Overview

This project detects AI-generated and manipulated face images using Deep Learning and Computer Vision techniques.

The project compares a classical machine learning baseline using Local Binary Patterns (LBP) and Random Forest with a Vision Transformer (ViT) model fine-tuned using Hugging Face Transformers.

---

## Problem Statement

DeepFake images are becoming increasingly realistic and difficult to identify manually.

This project aims to classify facial images into:

- Real
- Fake

using both traditional machine learning and transformer-based deep learning approaches.

---

## Dataset

Real and Fake Face Detection Dataset

Dataset Source:

https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection

Classes:

- Real Faces
- Fake Faces

Note:
The dataset is not included in this repository due to size limitations.

---

## Models Used

### Classical Machine Learning

- Local Binary Patterns (LBP)
- Random Forest Classifier

Results:

Accuracy: 49.5%

---

### Deep Learning

Vision Transformer (ViT)

Base Model:

google/vit-base-patch16-224-in21k

Frameworks:

- PyTorch
- Hugging Face Transformers

Training:

- Transfer Learning
- Fine-Tuning
- Binary Image Classification

Validation Accuracy Achieved:

~84.8%

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-Learn
- PyTorch
- Hugging Face Transformers

---

## Features

- DeepFake Image Detection
- Binary Classification
- Transfer Learning
- Vision Transformer Fine-Tuning
- Classical ML Baseline Comparison
- Real-Time Image Prediction

---

## Results

| Model | Accuracy |
|---------|---------|
| Random Forest + LBP | 49.5% |
| Vision Transformer (ViT) | ~84.8% |

The Vision Transformer significantly outperformed the classical machine learning baseline.

---

## Acknowledgements

This project uses the Vision Transformer (ViT) architecture provided through the Hugging Face Transformers library.

Base Model:

google/vit-base-patch16-224-in21k

---

## Author

Vamshi Krishna