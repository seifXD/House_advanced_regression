# House_advanced_regression

## Project Overview
This project focuses on predicting house prices using advanced machine learning techniques. The main goal is to develop models that can accurately estimate house prices based on various features such as the number of rooms, location, size, and more.

Two powerful models, XGBoost and LightGBM, were used in this project to improve prediction accuracy. These models are known for their performance in handling large datasets and delivering quick predictions.

## Dataset
The dataset used for this project contains various features about houses, such as:

Number of bedrooms
Square footage
Location
Year built
Additional amenities (e.g., garage, pool)
The data was preprocessed by handling missing values, performing feature scaling, and encoding categorical features.

## Key Features
XGBoost Model: A gradient boosting algorithm that is highly efficient for large datasets. It was fine-tuned using grid search to optimize hyperparameters for better performance.
LightGBM Model: Another gradient boosting model designed for efficiency and accuracy, particularly with large datasets and high-dimensional features.
Feature Engineering: Several new features were derived from the existing dataset to improve model performance.
Evaluation Metrics: The models were evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) to assess their accuracy.
## Notebooks and Files
House price prediction (XGB & LGBM).ipynb: The main Jupyter notebook containing all the steps from data preprocessing, feature engineering, model training, and evaluation.
