# 🧠 Face Recognition using Gaussian Naive Bayes (Olivetti Dataset)

This project implements a simple face recognition system using the [Olivetti Faces Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html) and the **Gaussian Naive Bayes classifier**. It is a classical machine learning approach to recognizing faces based on pixel intensity values.

---

## 📂 Dataset

- The dataset contains **400 grayscale face images** of **40 different people** (10 images per person).
- Each image is of size **64x64 pixels**.
- Data is loaded from a `.npy` file:  

---

## 🚀 Project Workflow

1. **Load the dataset** 
2. **Reshape** the images into 1D feature vectors
3. **Assign labels** (0–39) to represent individuals
4. **Split** the dataset into training and testing sets
5. **Train** a Gaussian Naive Bayes classifier
6. **Predict** and **evaluate** the model
7. **Visualize** a few predictions

---

## 🛠️ Tech Stack

- **Language**: Python 
- **Libraries**:
  - `NumPy`
  - `Matplotlib`
  - `scikit-learn`

---

## 📊 Model Evaluation

- **Classifier**: Gaussian Naive Bayes
- **Metrics**:
  - Accuracy
  - Classification report (precision, recall, F1-score)
  - Confusion matrix
- **Visualization**: Displays sample predictions with actual and predicted labels

---

## 📷 Output Sample

![Sample Output](preview.png) 

---

