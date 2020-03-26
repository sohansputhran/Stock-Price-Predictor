# Stock Market Prediction (Using LSTM)
Artificial recurrent neural network called Long Short Term Memory (LSTM) used to predict the closing stock price of a corporation (Apple Inc.) using the past 60 day stock price.

A LSTM network expects the input to be 3-Dimensional in the form [samples, time steps, features]: samples is the number of data points (or rows/ records) we have, time steps is the number of time-dependent steps that are there in a single data point (60), features/indicators refers to the number of variables we have for the corresponding true value in Y, since we are only using one feature 'Close', the number of features/indicators will be one.
