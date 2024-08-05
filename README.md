# House Price Prediction

## Overview
Welcome to house price prediction repository!The aim of the project is to predict house price for houses in Boston Housing Dataset.We leverage CatBoost for price prediction which is one of the advanced regression techniques.

## Data
The Ames Housing [dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) is taken from kaggle competition.
Two files, train and test are provided and the price of the test data is to be estimated.
Here I have used CatBoost for prediction.

I will be adding exploratory data analysis and compare the CatBoost model's result with other regression techniques later.
 
## Steps in House Price Prediction  

1. Loading data  
2. Data Exploration  
    2.1 Features with Null value  
    2.2 Numerical Features     
        
        2.2.1 Year Features
        2.2.2 Discrete Features    
        2.2.3 Continous Features 
        
    2.3 Categorical Features
3. Data Cleaning  
4. Data transformation  
   4.1 Rare Categorical Feature Handling  
5. Base Model Performance (CatBoost)
6. Hyperparameter Tuning With K Validation
7. Final Model

## Feature Engineering

For close price prediction using CatBoost, we have meticulously engineered a set of features to enhance our model's performance. These features include:

- Interaction Features
- Polynomial Features
- Log Transformation
- Binning
- Aggregation Features
- Date Features
- Encode categorical variables

Here, I have tried with lots of model such as SVM,Random Forest Regression,Linear Regression,XGBoost,LightGBM,Catboost and stacking regression.
<br>
Among all of these CatBoost stood-up.
## Result 
Got an MSE score of 0.013116839606646665 after hyperparameter tuning.
Got an RMSE score of 0.12376 on kaggle leaderboard.