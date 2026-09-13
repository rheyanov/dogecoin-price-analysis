# Dogecoin Price Analysis & Prediction

A data science project analyzing Dogecoin (DOGE-USD) price behavior and evaluating the predictive power of historical market data for short-term price movements.

## Overview

This project analyzes historical Dogecoin market data using exploratory data analysis, time-series feature engineering, and machine learning.

The analysis focuses on:
- Price trends and volatility
- Trading volume and abnormal market movements
- Short-term price direction prediction
- Comparison of regression and classification models

## Tech Stack

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

## Methods

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Time-series feature engineering
- Chronological 80/20 train-test split
- Feature scaling
- Linear Regression
- Logistic Regression
- Random Forest
- Model evaluation using RMSE, R², Accuracy, AUC-ROC, Precision, Recall, and F1 Score

## Key Findings

- Dogecoin exhibited substantial volatility, particularly during major market movements such as the 2021 price surge.
- Logistic Regression achieved slightly above 50% test accuracy for next-day price direction.
- Random Forest showed substantially stronger training performance than test performance, indicating overfitting.
- Historical price and volume features alone provided limited out-of-sample predictive power.

## Repository Structure

- `dogecoin_analysis.ipynb` — complete data analysis and modeling workflow
- `DOGE-USD.csv` — historical Dogecoin market data

## Authors

Team project by Yao Yao, Linying Wu Xie, and Youlan Zhao.
