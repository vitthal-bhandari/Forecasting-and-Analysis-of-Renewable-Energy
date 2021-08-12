# Forecasting-and-Analysis-of-Renewable-Energy
*Wind Speed Forecasting using SARIMA Modeling*

This project was completed in partial fulfilment of the course APPLIED STATISTICAL METHODS (MATH F432) offered during First Semester 2019-20 at BITS Pilani, Pilani Campus.

In our assignment, we analyzed the solar and wind energy for Charanka Solar Park (Gujarat) using hourly data and forecasted the wind speed for Jan 2011 by observing the existing time series trend from 2000‑2010 with a MAPE of 19.4

## What is ARIMA Forecasting?
Auto Regressive Integrated Moving Average (ARIMA) is a class of models that explains a given time series based on its own past values and the lagged forecast errors, so that equation can be used to forecast future values.

The autoregressive (AR) part of the model indicates the variable is regressed on its past values. The integrated (I) part for differencing process makes the series stationary. The moving average (MA) part indicates the regression error is a linear combination of error terms. All these parts need to be tuned to best fit the data.


## What is SARIMA Forecasting then?
```
If a time series, has seasonal patterns, then you need to add seasonal terms to the ARIMA model and it becomes SARIMA, short for ‘Seasonal ARIMA’.
```

## Which forecasting have we used?
Since our data has prominent seasonal component and apart from it the time series is stationary, therefore we use SARIMA model to forecast Wind-Speed data.

## Performance
With a Mean Absolute Percentage Error of 19.53%, we can conclude that the SARIMA forecasting model has a has a reasonable performance.

#### Want to know more?
Please read the [report](https://github.com/Vitthal98/Forecasting-and-Analysis-of-Renewable-Energy/blob/main/ASM%20ASSIGNMENT.pdf) as it contains detailed information about the datasets used, methods implemented, results obtained and further discussion.

For any doubts don't hesitate to contact me at vitthalbhandari98@gmail.com

If you find our work helpful, do not forget to :star: the repository!
