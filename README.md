# Bike Store Sales Forecasting

## Overview

This repository contains the code and dataset for forecasting the order quantity of a bike store chain's products based on historical sales data from 2011 to 2015. Developed a Gradient Boosting Regression model and a Random Forest Regressor model to predict future order quantities.

## Table of Contents

- [Dataset](#dataset)
- [Notebook](#notebook)
- [Results](#results)

## Dataset

The dataset used for this project is available in  `Sales.csv`. It includes historical sales data from 2011 to 2015, which serves as the foundation for training and testing the predictive model.

## Notebook

bike_sales_forecasting.ipynb contains is the Jupyter Notebook for this project. You can explore the entire data preprocessing, feature engineering, model development, and evaluation process in this notebook.

## Results
#### Here are the final evaluation metrics for both the models

#### For RandomForestRegressor :
| Data     | RMSE     | r2_score |
|----------|----------|----------|
| Train    | 4.04     | 82.34%   |
| Val      | 4.72     | 74.50%   |
| Test     | 4.77     | 73.98%   |

#### For GradientBoostingRegressor:
| Data     | RMSE     | r2_score |
|----------|----------|----------|
| Train    | 3.76     | 84.70%   |
| Val      | 4.16     | 80.18%   |
| Test     | 4.24     | 79.50%   |
