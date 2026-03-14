Customer Churn Prediction Using Machine Learning

Predicting customer churn is a critical problem for subscription-based businesses such as telecommunications, banking, and online services. In this project, a machine learning model is developed to predict whether a customer is likely to leave a company based on historical service usage and demographic data.

This project demonstrates the application of machine learning, exploratory data analysis used techniques to identify the key factors influencing customer churn.

Project Overview

The goal of this project is to develop a predictive model capable of identifying customers who are at high risk of leaving the service. Early prediction allows companies to take proactive retention measures.

Key steps in the project include:

Data preprocessing

Exploratory data analysis

Feature engineering

Machine learning model development

Model evaluation

Tools and Technologies

Programming Language
Python

Libraries Used

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

SHAP

Machine Learning Model

Random Forest Classifier
Dataset Description

The dataset contains customer information from a telecommunications company.

Main features include:
| Feature         | Description                |
| --------------- | -------------------------- |
| CustomerID      | Unique identifier          |
| Gender          | Male or Female             |
| SeniorCitizen   | Whether customer is senior |
| Tenure          | Months with company        |
| Contract        | Type of contract           |
| MonthlyCharges  | Monthly bill               |
| TotalCharges    | Total spending             |
| InternetService | Internet plan              |
| Churn           | Target variable            |

Exploratory Data Analysis

Exploratory data analysis was performed to understand patterns in customer behavior.

Churn Distribution

Customers who churn represent a significant portion of the dataset.
Correlation Heatmap

The heatmap highlights relationships between numerical features.
Machine Learning Model

A Random Forest Classifier was used for churn prediction because:

It handles nonlinear relationships

It reduces overfitting

It works well with mixed data types

The dataset was split into:

Training set: 80%
Testing set: 20%
Model Evaluation

The model was evaluated using several metrics:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

Key Business Insights

Customers with month-to-month contracts have the highest churn rate.

Customers with low tenure are more likely to leave.

Higher monthly charges increase churn probability.

Long-term contracts improve customer retention.

Business Recommendations

Companies can reduce churn by:

Offering incentives for long-term contracts

Providing targeted offers for new customers

Optimizing pricing strategies

Using predictive models for early churn detection
Future Improvements

Future improvements could include:

XGBoost and LightGBM models

Deep learning approaches

Real-time churn prediction systems

Customer lifetime value prediction
