
Stock Price Prediction Model

A neural net model to predict future stock prices based on previous stock prices and time features.
Based on the paper "How Much Can Time-related Features Enhance Time Series Forecasting?".
Link: https://arxiv.org/pdf/2412.01557

The model makes predictions based on the Closing price of a datapoint.

To evaluate the performance of the model, I created a linear regression model based on time lags to use as a baseline to compare performance.

In the future I plan to update the model to use lagged features as well as a lookback window to create predictions.
