# 🚦 Traffic Prediction Project

Welcome to the Traffic Prediction project repository! This project is focused on utilizing machine learning algorithms to accurately predict traffic flow and congestion patterns in Paris. By analyzing historical traffic data, we aim to provide insights that can help in traffic management, planning, and to reduce congestion.

## Overview 

This Traffic Prediction project leverages various data sources and machine learning techniques to forecast traffic conditions. The goal is to create a model that can predict traffic congestion levels for specific times and locations, helping in the optimization of traffic flows and reducing travel times.

## Features 

- **Data Collection**: Aggregation of historical traffic data from [Open Data Paris](https://opendata.paris.fr/pages/home/) to create a comprehensive dataset for analysis. We also used weather forecast, holidays, seasonal trends and more...
- **Data Preprocessing**: Cleaning and preparation of the dataset to ensure quality and relevance for model training like creating lags, converting categorical features to numerical...
- **Model Development**: Development and training of machine learning models to predict traffic conditions. We mainly used XGBoost but also tried complex models like RNN, LSTM or ARIMA models.
- **Evaluation**: Rigorous testing and evaluation of the models to assess their accuracy and reliability. The metric used here is RMSE but we also looked at MAPE to have a business friendly metric.
- **Visualization**: Interactive visualizations to represent the predictions and insights derived from the data.

## Technologies Used 

- **Python**: Primary programming language used for data preprocessing, model development, and evaluation.
- **Pandas & NumPy**: For data manipulation and numerical calculations.
- **Scikit-learn**: Employed for building and evaluating machine learning models.
- **Matplotlib & Seaborn**: Used for creating visualizations to represent data insights and predictions.
