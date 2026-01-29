# Online Transaction Fraud Detection using Machine Learning

## Overview
This project focuses on building a machine learning classification system to predict whether an online transaction is **LEGIT** or **FRAUD** using behavioral and contextual features.

## Objective
With the rapid growth of digital payments, detecting fraudulent transactions has become critical. This project aims to automate fraud detection and reduce manual review by applying supervised machine learning techniques.

## Dataset
The dataset contains both numerical and categorical features such as:
- Transaction amount
- Location and domain information
- Time-based variables
- Binary fraud indicators
- Derived behavioral features

## Data Preprocessing
- Missing numerical values handled using median
- Missing categorical values handled using mode
- Irrelevant columns removed to reduce noise
- Categorical features encoded
- Data split into training and testing sets

## Models Implemented
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

## Model Evaluation
Models were evaluated using:
- Accuracy score
- Confusion matrix

Random Forest achieved the highest accuracy and most stable performance and was selected as the final model.

## Use Case
This system can support:
- Banking fraud detection
- Fintech transaction monitoring
- E-commerce payment security

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Naja Nesrin

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<najanezrin>/online-transaction-fraud-detection.git
   cd online-transaction-fraud-detection
   pip install -r requirements.txt
   

