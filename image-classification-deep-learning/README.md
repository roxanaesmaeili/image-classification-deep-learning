# Sports Image Classification using Deep Learning

## Overview

This project develops a deep learning image classification system capable of recognising **100 different sports categories** using transfer learning. Multiple convolutional neural network (CNN) architectures and optimisation strategies were evaluated to improve classification performance on a large-scale image dataset.

The project compares several deep learning experiments based on **ResNet18** and **EfficientNet-B0**, demonstrating how transfer learning, optimiser selection, data augmentation and learning-rate scheduling influence model performance.

---

## Key Features

- Transfer Learning with pretrained CNNs
- Multi-class Image Classification (100 sports)
- Model Comparison and Performance Evaluation
- Data Augmentation
- Hyperparameter Optimisation
- Deep Learning using PyTorch
- Computer Vision

---

## Business Applications

Image classification has a wide range of real-world applications, including:

- Medical image diagnosis
- Autonomous vehicles
- Intelligent surveillance
- Sports analytics
- E-commerce product recognition
- Industrial quality inspection

---

## Dataset

**Dataset:** Sports Image Classification Dataset (Kaggle)

The dataset contains images organised into training, validation and test sets covering **100 different sports categories**.

Approximate dataset size:

| Dataset | Images |
|---------|--------:|
| Training | 13,492 |
| Validation | 500 |
| Test | 500 |

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Transfer Learning
- Jupyter Notebook

---

# Project Workflow

1. Data Loading
2. Image Preprocessing
3. Data Augmentation
4. Transfer Learning
5. Model Training
6. Hyperparameter Optimisation
7. Performance Evaluation
8. Model Comparison
9. Error Analysis

---

# Sample Images

![Sample Images](images/sample_dataset_images.png)

The dataset contains a diverse collection of sports images with different lighting conditions, viewpoints, backgrounds and object scales, making the classification task significantly more challenging.

---

# Model Comparison

The following experiments were conducted throughout the project.

| Experiment | Test Accuracy |
|------------|--------------:|
| ResNet18 (Baseline) | **78.0%** |
| ResNet18 + Data Augmentation | **89.4%** |
| ResNet18 + SGD Optimiser | **93.8%** |
| ResNet18 + Learning Rate Scheduler | **94.4%** |
| EfficientNet-B0 | **97.6%** |

---

## Accuracy Comparison

![Accuracy Comparison](images/model_accuracy_comparison.png)

The experiments demonstrate that optimiser selection and model architecture significantly improved classification performance. EfficientNet-B0 achieved the highest test accuracy while maintaining computational efficiency.

---

# Model Architecture

The project compares two popular convolutional neural network architectures:

### ResNet18

- Residual learning architecture
- Pretrained on ImageNet
- Strong baseline model
- Lightweight and efficient

### EfficientNet-B0

- Compound scaling architecture
- Higher accuracy with fewer parameters
- Excellent computational efficiency
- Best overall performance

---

# Results

The final **EfficientNet-B0** model achieved:

- ✅ **97.6% Test Accuracy**
- Transfer learning using ImageNet weights
- Strong generalisation across 100 image classes
- Improved computational efficiency compared with larger CNN architectures

---

# Error Analysis

![Misclassified Images](images/misclassified_examples.png)

Visual inspection of incorrectly classified images revealed that most errors occurred between visually similar sports. This analysis provides valuable insight into model behaviour and highlights opportunities for future improvement.

---

# Skills Demonstrated

- Deep Learning
- Computer Vision
- Transfer Learning
- PyTorch
- CNN Architecture
- Data Augmentation
- Hyperparameter Optimisation
- Model Evaluation
- Multi-class Classification
- Performance Comparison
- Error Analysis

---

# Future Improvements

Potential future enhancements include:

- Vision Transformers (ViT)
- Larger and more diverse datasets
- Hyperparameter optimisation using Optuna
- Distributed GPU training
- Model deployment with Streamlit
- Explainable AI techniques such as Grad-CAM

---

# Repository Structure

```text
image-classification-deep-learning/
│
├── notebooks/
│   └── sports_image_classification.ipynb
│
├── report/
│   └── BigData-Report.pdf
│
├── images/
│   ├── sample_dataset_images.png
│   ├── model_accuracy_comparison.png
│   └── misclassified_examples.png
│
└── README.md
```

---

# Author

**Roxana Esmaeili**

BSc Data Science & Artificial Intelligence  
University of Portsmouth
