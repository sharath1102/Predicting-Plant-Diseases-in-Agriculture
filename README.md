# 🌿 Deep Learning for Predicting Plant Diseases in Agriculture

This project focuses on using deep learning techniques to identify and classify plant diseases from leaf images, aiming to support early detection and promote healthier crop yield. The primary goal is to provide farmers and agricultural experts with a scalable, image-based tool for accurate and timely plant disease diagnosis.

## 📌 Project Overview

Agriculture is often affected by various plant diseases that reduce productivity and increase losses. Manual disease identification is time-consuming and prone to error. This project leverages a hybrid **Convolutional Neural Network (CNN)** to automatically detect rice plant diseases such as:

- Brown Spot
- Bacterial Leaf Blight
- Leaf Smut

The model is trained on a dataset of leaf images and achieves high accuracy by combining effective preprocessing, deep learning techniques, and evaluation metrics.

## 🧠 Key Features

- ✅ CNN-based classification model tailored for rice leaf disease detection.
- 📸 Image preprocessing using techniques like **Gaussian blur**, **normalization**, and **resizing**.
- 🧪 Model evaluation using **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.
- 📊 Comparative analysis with traditional ML models like **SVM**, **KNN**, and **Random Forest**.
- 📈 Achieved an overall model accuracy of **87%**.
- ☁️ Designed for cloud deployment and edge-device compatibility.
- 🌍 Real-time detection potential through mobile/web integration.

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Scikit-learn  
- **Platform**: Google Colab / Jupyter Notebook  

## 🧪 How It Works

1. **Data Collection**  
   - Leaf images of diseased and healthy plants are collected and organized into labeled folders.

2. **Data Preprocessing**  
   - Images are resized, normalized, and augmented.
   - Noise is reduced using Gaussian blur and filtering techniques.

3. **Model Building**  
   - A custom CNN architecture is designed with multiple convolutional and pooling layers.
   - Dense layers and dropout layers are added for better generalization.

4. **Training & Evaluation**  
   - The model is trained and validated on split datasets.
   - Performance is measured using evaluation metrics.

5. **Comparison & Deployment**  
   - Compared CNN performance with traditional classifiers.
   - Prepared for deployment in future mobile or IoT-based applications.

## 📂 Folder Structure

```plaintext
├── data/
│   ├── train/
│   └── test/
├── model/
│   └── plant_disease_cnn.h5
├── notebooks/
│   └── PlantDiseaseDetection.ipynb
├── README.md
└── requirements.txt
