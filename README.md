# Fraud Detection with Machine Learning

## Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions.  
It includes data preprocessing, feature engineering with temporal aggregations, and model training.

## Dataset
Dataset: Credit Card Fraud Dataset (Kaggle)  
Features include anonymized PCA components, transaction amount, and time-based features.

## Feature Engineering
- Transaction velocity features (transactions per day)
- Rolling window statistics (1D, 7D average amount)
- Customer behavioral features
- Merchant-level aggregations

## Data Pipeline
1. Normalize raw data into tables: transactions, customers, merchants  
2. Generate feature tables  
3. Merge features into final training dataset  
4. Train Random Forest model

## Models
- Random Forest

## Params
- used RandomizedSearchCV to find best params
- 
## Evaluation Metrics
- Precision-Recall curve
- F1-score

## Results
precision - 85
recall - 81

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Google Colab
