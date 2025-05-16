# 🧠 Multimodal Deep Learning for Brain Tumor Classification

A deep learning-based diagnostic system that utilizes MRI brain scans to classify tumors into four categories using a hybrid DenseNet121 + U-Net architecture. The system aims to support radiologists and healthcare professionals with fast, accurate, and automated brain tumor detection.

## 🩺 Project Overview

This project presents a multimodal approach combining transfer learning and custom decoding to classify MRI brain images into the following tumor types:
- **Glioma**
- **Meningioma**
- **Pituitary**
- **No Tumor**

The model leverages DenseNet121 as a feature extractor and integrates custom decoder layers similar to U-Net for precise and efficient classification.

## ✅ Key Features

- 🔍 High-accuracy tumor classification from MRI images
- 🧠 Hybrid model: **DenseNet121 + U-Net-inspired decoder**
- ⛔ Early stopping, dropout, and batch normalization to avoid overfitting
- 🖼 Image preprocessing using OpenCV for noise reduction and contrast enhancement
- 📊 Visual performance reports (confusion matrix, accuracy/loss plots)
- 🎯 Achieved **98% test accuracy**

## 🧪 Technologies Used

- **Programming Language**: Python
- **Libraries/Frameworks**:
  - TensorFlow & Keras
  - OpenCV
  - scikit-learn
  - Matplotlib & Seaborn
  - NumPy, Pandas

## 📁 Dataset

- MRI Brain Tumor Images Dataset
- Organized in folders by tumor class:
  - `glioma/`, `meningioma/`, `pituitary/`, `no_tumor/`
- Dataset split: Train / Test

*(You can use publicly available datasets such as the Kaggle Brain MRI Dataset or your own labeled dataset.)*



