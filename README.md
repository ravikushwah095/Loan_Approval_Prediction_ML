# Loan Eligibility Prediction using Machine Learning

## Project Overview

This project aims to predict whether a customer's loan application will be approved or rejected using machine learning classification algorithms.

The dataset contains customer information such as income, education, credit history, loan amount, property area, and other financial details. The goal is to automate the loan eligibility prediction process.

---

## Problem Statement

Dream Housing Finance wants to automate the loan approval process by identifying customers who are eligible for loan approval based on their application details.

This project builds a classification model to predict:

- Loan Approved (Y)
- Loan Rejected (N)

---

## Dataset Features

The dataset contains the following features:

- Gender
- Married Status
- Dependents
- Education
- Self Employment Status
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area

Target Variable:

- Loan_Status

---

## Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Encoding categorical variables
- Removing unnecessary features
- Feature scaling using StandardScaler
- Train-test split

---

## Machine Learning Models Used

### 1. Logistic Regression

A supervised classification algorithm used as the baseline model.

### 2. Gaussian Naive Bayes

A probabilistic classification algorithm based on Bayes theorem.

---

## Model Evaluation

Models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve

---

## Results

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 78.86% | 0.741 |
| Gaussian Naive Bayes | 78.05% | 0.735 |

Logistic Regression achieved slightly better performance compared to Gaussian Naive Bayes and was selected as the final model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

Data Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Model Training
↓
Model Evaluation
↓
ROC-AUC Comparison
## Conclusion

The project successfully predicts loan eligibility using machine learning classification techniques. Logistic Regression provided the best performance among the tested models with better accuracy and ROC-AUC score.

---

## Author

Ravi Kushwah
