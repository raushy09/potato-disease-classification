# 🥔 Potato Disease Classification

## 📌 Overview

This project uses a Convolutional Neural Network (CNN) to classify potato leaf images into different disease categories. The model was developed using TensorFlow/Keras and the trained model was integrated into a Streamlit application for image-based prediction.

## 🎯 Objective

The objective is to develop an image classification system that can identify whether a potato leaf is healthy or affected by a specific disease based on an uploaded image.

## 🗂️ Classes

The model classifies images into:

* Potato Early Blight
* Potato Late Blight
* Potato Healthy

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* CNN
* NumPy
* Pandas
* Matplotlib
* Streamlit
* Jupyter Notebook

## 🔄 Project Workflow

```text
Image Dataset
      ↓
Image Preprocessing
      ↓
Data Augmentation
      ↓
CNN Model
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Streamlit Deployment
      ↓
Disease Prediction
```

## 🧠 Model

A Convolutional Neural Network (CNN) was developed to learn visual patterns from potato leaf images and classify them into the corresponding disease categories.

The preprocessing pipeline includes image resizing, normalization, and data augmentation to improve model generalization.

## 📊 Model Evaluation

The model was evaluated using validation/test data and classification performance metrics.

> Add your actual accuracy/validation accuracy here.

## 🚀 Streamlit Application

The trained model was integrated into a Streamlit application where users can upload a potato leaf image and receive:

* Predicted disease class
* Prediction confidence

## 💻 How to Run

Clone the repository:

```bash
git clone https://github.com/raushy09/potato-disease-classification.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

## 📁 Project Structure

```text
potato-disease-classification/
│
├── Potato_Disease_Classification.ipynb
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 👨‍💻 Author

**Raushan Kumar**

NIT Patna | Mechanical Engineering + AI Minor
