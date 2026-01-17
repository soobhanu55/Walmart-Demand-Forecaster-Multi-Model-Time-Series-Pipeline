# Walmart Demand Forecaster: Multi-Model Time Series Pipeline

## 📌 Project Overview
This project is an end-to-end demand forecasting solution developed using the Walmart M5 dataset. It focuses on predicting sales at a granular level (item-store-day) by accounting for external factors like price changes, promotions (SNAP), and calendar events.

## 🚀 Key Features
* **Multi-Model Approach**: Comparison of diverse forecasting techniques including:
    * **Traditional**: ARIMA, Exponential Smoothing, and Holt-Winters.
    * **Machine Learning**: XGBoost Regressor and Random Forest.
    * **Modern Forecasting**: Facebook Prophet.
* **Advanced Signal Processing**: Implements Denoising techniques using Wavelet Transform (`pywt`) to remove noise from volatile sales data.
* **Comprehensive EDA**: In-depth visualization of sales trends across states (CA, TX, WI) using interactive Plotly charts.
* **External Variable Integration**: Correlates demand with calendar events and SNAP benefit cycles.

## 🛠️ Technical Stack
* **Algorithms**: XGBoost, Random Forest, Prophet, ARIMA.
* **Signal Processing**: PyWavelets (pywt), SciPy.
* **Interactive Visualization**: Plotly, Seaborn.
* **Tools**: Scikit-learn, Statsmodels.

## 📂 Dataset
Uses the hierarchical Walmart M5 forecasting data, including `calendar.csv`, `sales_train.csv`, and `sales_price.csv`.
