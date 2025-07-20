# 📊 Customer Churn Prediction

This project focuses on predicting customer churn using machine learning. It includes data preprocessing, model training, evaluation, and deployment via a Streamlit web application. The goal is to help telecom or subscription-based companies proactively identify customers likely to leave.

## 🚀 Project Overview

- **Objective**: Predict whether a customer will churn based on demographic and service-related features.
- **Tech Stack**: 
  - Python (Pandas, Scikit-learn)
  - Jupyter Notebook
  - Streamlit
  - Git/GitHub

## 🧠 Machine Learning Model

- **Model Used**: Logistic Regression (or any other if you used something else)
- **Training Data**: Cleaned and preprocessed telecom dataset.
- **Target Variable**: `Churn` (Yes/No)

## 📁 Project Structure

│
├── churn_model.pkl # Trained model
├── sample_input_encoded.csv # Sample encoded input data for predictions
├── churn_prediction_app.py # Streamlit web app
├── model_training.ipynb # Jupyter Notebook for training and evaluation
├── sample_input_generator.ipynb # Notebook to generate encoded CSV sample
├── requirements.txt # List of required Python packages
└── README.md # Project documentation

## 📈 Model Performance
Accuracy: ~85% (example value)

Evaluation Metrics: Confusion matrix, precision, recall, F1-score

## 📌 Features Used
Demographics: Gender, SeniorCitizen, Partner, Dependents
Services: InternetService, StreamingTV, etc.
Account Info: Contract type, MonthlyCharges, TotalCharges, etc.

## 💡 Future Improvements
Use advanced models like XGBoost or RandomForest
Feature engineering and hyperparameter tuning
