# 🚀 RT-IoT2022 Regression using ML & DL

## 📌 Project Overview

This project focuses on predicting **network flow duration** using both Machine Learning (ML) and Deep Learning (DL) techniques on the RT-IoT2022 cybersecurity dataset.

The goal is to accurately estimate continuous `flow_duration` values from network traffic features.

The models are trained on RT-IoT2022, a real-world IoT network traffic dataset containing protocol, service, and flow-based statistical features.

---

## 🎯 Objectives

* Apply multiple ML and DL algorithms to a real-world cybersecurity regression dataset
* Compare model performance using standard regression metrics
* Identify the best-performing model for flow duration prediction
* Demonstrate practical application of AI in cybersecurity analytics

---

## 📂 Dataset Information

**Dataset Name:** RT-IoT2022
**Type:** Regression
**Features:** 50 network traffic flow features
**Target Variable:** `flow_duration`

### Dataset Includes:

* Protocol information (`proto`)
* Service type (`service`)
* Statistical traffic features
* Flow-based measurements

---

## 🧠 Models Implemented

### 🔹 Machine Learning Models

* Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet Regression

### 🔹 Deep Learning Models

* Deep Neural Network (MLP / Keras)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Handling skewed target values
* Log transformation (`log1p`)
* Winsorization for outlier reduction
* One-hot encoding categorical variables
* Feature scaling
* Correlation pruning
* Feature selection (`SelectKBest`)

### 2. Exploratory Data Analysis (EDA)

* Data distribution analysis
* Missing value inspection
* Correlation heatmap
* Outlier visualization

### 3. Model Training

* Training ML and DL models
* Hyperparameter tuning
* Performance optimization

### 4. Model Evaluation

Models are evaluated using:

* MSE (Mean Squared Error)
* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## 📊 Results Summary

The models were compared based on regression performance metrics, and:

### ✅ Linear Regression achieved the best overall performance

* Lowest error rates
* Highest R² score
* Extremely fast training time
* Strong predictive capability after preprocessing

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn
* TensorFlow / Keras
* Joblib

---

## 📥 Clone the Repository

```bash
git clone https://github.com/your-username/rt-iot2022-regression.git
cd rt-iot2022-regression
```

---

## 📈 Key Highlights

* Combines ML + DL approaches in one project
* Works on a real cybersecurity IoT dataset
* Demonstrates complete regression pipeline
* Includes feature engineering + optimization
* Suitable for academic + portfolio use

---

## 🔐 Applications

* IoT Traffic Analysis
* Network Performance Prediction
* Cybersecurity Monitoring
* Intelligent Traffic Analytics
* Anomaly Detection Support Systems

---

## 👤 Author

**Name:** Vineel Bokkinala
**Student ID:** 25165675

---

## 📌 Future Improvements

* Implement XGBoost / LightGBM
* Add SHAP explainability
* Use time-series architectures (LSTM)
* Real-time deployment pipeline
* Ensemble model stacking

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub and feel free to fork it!
