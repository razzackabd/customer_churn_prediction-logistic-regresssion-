# customer_churn_prediction-logistic-regresssion-
Customer Churn Prediction Using Logistic Regression
📊 Customer Churn Prediction using Logistic Regression
📌 Project Overview

Customer churn prediction is a common and important machine learning use case in industries like telecom, banking, and SaaS. This project focuses on predicting whether a customer is likely to churn (leave the service) using Logistic Regression, a simple yet powerful supervised learning algorithm.

The goal is to build an interpretable and efficient binary classification model that helps businesses take proactive retention actions.

🧠 Problem Statement

To predict whether a customer will churn based on historical customer data such as:

Demographics

Account information

Service usage patterns

Target Variable:

Churn → Yes (1) / No (0)

🛠️ Tech Stack

Programming Language: Python

Libraries Used:

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

IDE / Environment: Jupyter Notebook

📂 Dataset Description

The dataset contains customer-level information including:

gender

SeniorCitizen

Partner

Dependents

tenure

MonthlyCharges

TotalCharges

Churn

Note: The dataset is preprocessed to handle missing values and categorical features.

🔄 Project Workflow

Data Loading & Exploration

Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling using StandardScaler

Train-Test Split

Model Building (Logistic Regression)

Model Evaluation

Accuracy Score

Confusion Matrix

Classification Report

Result Interpretation

🤖 Model Used
Logistic Regression

Logistic Regression is used for binary classification problems. It estimates the probability that a given input belongs to a particular class using the sigmoid function.

Why Logistic Regression?

Simple and interpretable

Fast training

Works well for linearly separable data

📈 Model Performance

Evaluation metrics used:

Accuracy

Precision

Recall

F1-Score

The model provides a reliable baseline for churn prediction and can be improved further using advanced algorithms.

📊 Results & Insights

Customers with short tenure are more likely to churn

Higher monthly charges increase churn probability

Customers without partners or dependents show higher churn rates
Run the Jupyter Notebook

🙌 Conclusion

This project demonstrates how Logistic Regression can be effectively used for customer churn prediction. It serves as a strong foundation for beginners and can be extended into a production-level machine learning system.
