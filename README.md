# 🌿 Plant Leaf Disease Detection using CNN

## 📌 Project Overview

This project is a Deep Learning based image classification system that detects plant leaf diseases using a Convolutional Neural Network (CNN).

The model is trained on the PlantVillage dataset and can classify different plant leaf diseases from an uploaded image.

---

## 🎯 Objective

To build a machine learning model that can:
- Detect plant leaf diseases
- Classify leaf images into multiple disease categories
- Help farmers identify plant diseases early

---

## 🧠 Algorithm Used

- Convolutional Neural Network (CNN)
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Image Size: 128x128
- Epochs: 5

This is a multi-class image classification problem.

---

## 📂 Dataset

Dataset used: PlantVillage Dataset  
Source: Kaggle  

The dataset contains:
- 54,000+ images
- 38 different plant disease classes

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

---

## 🏗️ Model Architecture

The CNN model consists of:

- Conv2D Layer (32 filters)
- MaxPooling Layer
- Conv2D Layer (64 filters)
- MaxPooling Layer
- Conv2D Layer (128 filters)
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (Softmax activation)

---

## 📊 Model Performance

- Training Accuracy: ~95%
- Validation Accuracy: ~89–90%

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
   ```
   pip install tensorflow numpy matplotlib
   ```
3. Download dataset using Kaggle API
4. Run the notebook
5. Upload a leaf image to get disease prediction

---

## 🖼️ Prediction Example

Upload a leaf image and the model will output:

Predicted Disease: Tomato___Late_blight

---

## 🎓 Project Type

Deep Learning  
Multi-Class Image Classification  

---


## 👨‍💻 Author

Wajahat Bine Saif 
BSCS 7th Semester 
Machine Learning Project
