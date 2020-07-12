# Forecasting product demand using SARIMA 

### Problem Statement

It is obligatory for any manufacturing firm to maintain continuity of its **supply chain** to meet customer needs timely. However, at today's global scale the products go through complex supply chain networks needing large shipping times. Thus, there are chances of inventory stock-out if the products are not shipped timely. It is important for the company to **predict the demand** to avoid inventory stock-out, thereby reducing the total lead time of the products. Thus, a forecasting model that can efficiently predict the product demand of a manufacturing company helps the company overcome situations of stock-out and help it plan production needs efficiently. 

### Objective

The objective of the project is to use demand data from [Superstore data](https://www.kaggle.com/felixzhao/productdemandforecasting) on Kaggle for a global company, and analyze the demand rates of the warehouse over a span of four years and develop a forecasting model to predict the demand for the month after next month in advance for products having less variability in demand as well having large variability in demand. 

### Dataset

The dataset with 25,035 unique values and 24 attributes contains product demand data over a 4 year period between 2011-2015. 

### Timeseries Analysis 

* Holt-Winter's Seasonal Method

![Holt Visualization](/Holt_Visualization.PNG)

* Timeseries Analysis using Seasonal Autoregressive Integrated Moving Average (SARIMA)

![SARIMA Visualization](/Sarima_Visualization.PNG)

### Result Comparison

Forecasting Models | Root Mean Square Error | Mean Absolute Percentage Error
------------ | ------------- | -------------
Exponential Smoothing Model | 1894.09 | 10.09
Holt's Method using Static Seasonality Indices | 1458.29 | 8.03
Holt-Winter's Seasonal Method | 1435.23 | 7.11
Seasonal ARIMA (SARIMA) | 1810.3 | 8.67



