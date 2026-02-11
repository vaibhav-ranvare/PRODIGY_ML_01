# PRODIGY_ML_01
House Price Prediction – Linear Regression  This project implements a Multiple Linear Regression model to predict house prices using selected features from the Kaggle House Prices – Advanced Regression Techniques dataset.  The model predicts house prices based on: GrLivArea, BedroomAbvGr, FullBath


House Price Prediction using Multiple Linear Regression

Project Overview
This project implements a Multiple Linear Regression model to predict house prices using selected features from the Kaggle House Prices – Advanced Regression Techniques dataset.

The model estimates the sale price of a house based on:-
GrLivArea – Above-ground living area (square footage)
BedroomAbvGr – Number of bedrooms
FullBath – Number of full bathrooms

Objective
To build a regression model that learns the relationship between house characteristics and sale price, and evaluate its predictive performance using standard regression metrics.

Dataset -
Source: Kaggle – House Prices: Advanced Regression Techniques
File Used: train.csv
Target Variable: SalePrice
Dataset Link:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

Technologies & Libraries -
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Machine Learning Workflow -
Data Loading
Feature Selection
Data Cleaning
Exploratory Data Analysis (EDA)
Train-Test Split
Model Training (Linear Regression)
Model Evaluation
Price Prediction

Model Used -
Multiple Linear Regression

Mathematical Representation:- SalePrice = b0 ​+ b1​(GrLivArea) + b2​(Bedrooms) + b3​(FullBath)

Where: 
b0 = Intercept 
b1,b2,b3 = Model coefficients

Model Evaluation Metrics
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score
