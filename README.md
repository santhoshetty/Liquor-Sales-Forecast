# Liquor-Sales-Forecast

This notebook demonstrates time-series prediction.

Problem Description: Data was downloaded from [US Census Bureau monthly liquor sales](https://www.census.gov/econ/currentdata/dbsearch?program=MRTS&startYear=1992&endYear=2018&categories=44X72&dataType=SM&geoLevel=US&adjusted=1&notAdjusted=1&errorData=0%3EUnited). The aim is forecast the monthly liquor sales for the next 14 months using historical data.

A SARIMAX (variant of ARIMA) was used to predict the next 14 months liquor sales with RMSE ~ 85 Million Dollars which corresponds to 1.76% of the average monhtly sale of 4276 Million Dollars.

The notebook contains the following:
1. Making the time-series stationary and stationarity tests.
2. Using auto-correlation and partial auto-correlation plots to find the orders of the auto-regressive and moving-average orders.
3. Analysis and incorporation of seasonality in the trend.
4. Using a grid-search to automatically select the best orders to forecast.
5. Analysis of the final ARIMA model results, including residuals. 

This notebook is a practice of the [PyData Conference in 2016 by Jeffrey Yau](https://www.youtube.com/watch?v=tJ-O3hk1vRw).
