# Analysis and Forecasting of Time Series Data
This repository contains time series analysis and forecasting of monthly electricity generation data (USMELEC).

USMELEC dataset demonstrates the monthly electricity net generation in the United States between January 1973 - June 2013. It contains 486 rows and 3 columns which are year, month, and value showing generation on that date.

This repository includes exploratory data analysis, feature engineering and modeling parts.

Exploratory data analysis is the analysis of dataset based on numerical methods and graphical tools. It aims to
explore data for patterns, trends, and deviations, and to visualize data with histograms, line
plots, autoregression plots, or scatter plots.

Data analysis checks :
  - Stationarity
  - Seasonality
  - Autocorrelation
  
Generally, time series data contains only date and value columns, such as the USMELEC
dataset. Feature engineering means extracting new features from date and value to get accurate predictions.

Extracted features to increase accuracy are :
  - Lagging
  - Rolling window
  - Encoding

Models used for forecasting are :
  - Linear Regression
  - Support Vector Regression
  - Random Forest
  - LightGBM
  - XGBoost
  - ARIMA/ SARIMAX
  - LSTM
  - Multilayer Perceptron (MLP)
  
In addition, K-Fold Cross Validation used to choose the best models and Grid Search is used to find the best hyperparameters that gives higher accuracies. 
  
