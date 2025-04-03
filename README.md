README FOR PROJ 1 : ***Comparative Analysis of Random Forest and LSTM for Stock Price Prediction***

**Stock Price Prediction with Machine Learning**
-----------------------------------------------------------------------------------------------------------------------------------
*Project Overview*

This project predicts future stock prices (AAPL) using Random Forest and LSTM models. Key components include:

1.Data collection from Yahoo Finance API

2.Exploratory Data Analysis (EDA)

3.Feature engineering for time series

4.Model training and evaluation

5.Performance comparison between traditional ML and deep learning approaches

-----------------------------------------------------------------------------------------------------------------------------------
**Technical Implementation**

*Key Features*

1.Data Pipeline: Automated retrieval of stock data using yfinance

2.Feature Engineering: Generation of technical indicators (moving averages, RSI)

**Model Architecture:**

1.Random Forest with feature importance analysis

2.LSTM network for sequential pattern recognition

**Evaluation Metrics: RMSE and MAE for both training and test sets**
-----------------------------------------------------------------------------------------------------------------------------------
Results Summary

Model	          |       Train RMSE | Test RMSE | Train MAE | Test MAE

Random Forest 	|          2.34	  |   3.56	  |    1.89	  |  2.45

LSTM	          |          1.78	  |   2.91	  |    1.32	  |  1.98
-----------------------------------------------------------------------------------------------------------------------------------

***Customization Options***

**Changing Assets**

Modify the ticker symbol in the notebook:

ticker = 'MSFT'  # Supports any Yahoo Finance symbol

**Model Parameters**

Adjust the LSTM lookback window:

time_step = 30  # Default: 60 days

***********************************************************************************************************************************
***GENERAL DESCRIPTION OF THIS PROJECT:***
This project compares Random Forest and LSTM models for predicting Apple Inc. (AAPL) stock prices using historical market data. 

Designed as an end-to-end machine learning pipeline, it demonstrates:

Time series forecasting techniques

Feature engineering for financial data

Model evaluation with quantitative metrics (RMSE, MAE)

Visualization of predictions vs. actual prices

Key Features
Data Pipeline: Automated data fetching from Yahoo Finance (yfinance)

Modular Code:

data_preprocessing.py: Handles feature creation and normalization

model_training.py: Implements and evaluates both models

***********************************************************************************************************************************

