# ❤️ Heart Disease Prediction System

## 📌 Overview

This project is a Machine Learning-based classification system that predicts whether a person is at risk of heart disease based on their medical attributes. The model is built using Python and evaluates patient data to assist in early detection of heart disease.

---

## 🎯 Objective

The main goal of this project is to:

* Analyze medical data of patients
* Identify patterns related to heart disease
* Build a predictive machine learning model
* Support early diagnosis and healthcare decision-making

---

## 📊 Dataset

The dataset used is the **Heart Disease UCI Dataset**, which includes the following features:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Serum Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate Achieved
* Exercise Induced Angina
* Oldpeak (ST depression)
* Target (0 = No Disease, 1 = Disease)

---

## 🛠 Libraries Used

The following Python libraries are used in this project:

* pandas → Data handling
* numpy → Numerical operations
* matplotlib → Visualization
* seaborn → Statistical plotting
* scikit-learn → Machine learning algorithms and evaluation

---

## 🔄 Workflow

The project follows these steps:

1. Import required libraries
2. Load dataset into Pandas DataFrame
3. Perform data inspection (shape, info, head)
4. Handle missing values (if any)
5. Exploratory Data Analysis (EDA)

   * Target distribution
   * Age vs disease analysis
   * Correlation heatmap
6. Split dataset into features (X) and target (y)
7. Train-test split
8. Train Logistic Regression model
9. Make predictions on test data
10. Evaluate model performance:

* Accuracy Score
* Confusion Matrix
* ROC Curve & AUC Score

11. Feature importance analysis
12. Draw conclusions and insights

---

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* ROC-AUC Curve

---

## 🔍 Key Insights

* Chest pain type is a strong indicator of heart disease risk
* Age and cholesterol levels significantly impact prediction
* Maximum heart rate is an important feature for classification

---


