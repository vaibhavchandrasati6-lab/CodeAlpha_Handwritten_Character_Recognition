# 🧠 Handwritten Character Recognition 

This project was developed as part of my **CodeAlpha Internship (Project 3)**.  
It demonstrates a deep learning approach to classify handwritten digits using a Convolutional Neural Network (CNN).

---

## 📌 Project Overview

The goal of this project is to build a model that can correctly recognize digits (0–9) from images using the **MNIST dataset**.

The model is built using a **Convolutional Neural Network (CNN)** which is highly effective for image classification tasks.

---

## 📊 Dataset

We used the **MNIST dataset**  

- 60,000 training images  
- 10,000 testing images  
- Image size: 28 × 28 pixels  
- Grayscale images  
- Classes: 10 (digits 0–9)

---

## 🧠 Model Architecture

The model is built using a CNN:

- Conv2D (128 filters, 2×2 kernel)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Conv2D (32 filters)
- MaxPooling2D
- Flatten layer
- Dense (100 neurons)
- Dense (50 neurons)
- Dense (10 neurons - Output layer)

---

## 🔄 Workflow

1. Load MNIST dataset  
2. Normalize images (0–1 scaling)  
3. Reshape images to (28, 28, 1)  
4. Build CNN model  
5. Train the model  
6. Evaluate model  
7. Predict digits

---

## 📈 Model Performance

- 🎯 Training Accuracy: **99.30%**
- 🎯 Testing Accuracy: **98.40%**

The model shows strong generalization with minimal overfitting.

---

## 📌 Conclusion

This project helped in understanding:
- Convolutional Neural Networks (CNN)
- Image preprocessing and reshaping
- Deep learning model training
- MNIST digit classification
- Achieving high accuracy (98–99%)
