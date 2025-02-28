# Modeling Microsoft Stock Price Over Time: Utilizing ARIMA and GARCH

## Project Overview
This project analyzes and forecasts Microsoft (MSFT) stock prices from 2016 to 2020 using time series models. The goal is to leverage ARIMA to model stock price trends and GARCH to capture volatility. The study provides insights into stock price behavior and potential future movements.

## Dataset
Source: Microsoft Stock Time Series Analysis (Kaggle)
Time Period: January 2016 – December 2020
Frequency: Monthly average closing prices

## Methodology
1. ARIMA Model (AutoRegressive Integrated Moving Average)
- Used for capturing the stock price trend
- Differencing applied to ensure stationarity
- Model selection based on ACF/PACF plots and AIC/BIC

2. GARCH Model (Generalized AutoRegressive Conditional Heteroskedasticity)
- Used to model stock price volatility
- Accounts for volatility clustering in financial data
- GARCH(1,1) selected as the optimal model

## Results
ARIMA(0,1,0) with GARCH(1,1) provided the best fit. The model successfully captured trend and volatility dynamics. Forecasted Microsoft’s stock price for the next 12 months

## Future Improvements
- Use daily instead of monthly data for better granularity
- Incorporate seasonality using SARIMA
- Explore alternative models like LSTM neural networks
- Include external factors such as economic indicators and company financials

## How to run the project/make edits
Download the microsoft stock price dataset from Kaggle. Ensure necessary R libraries are installed, as listed at the top of the rmd file. Run the provided chunks and make edits as you please.

## Author
Will Markevitch
wmarkevitch@ucsb.edu
