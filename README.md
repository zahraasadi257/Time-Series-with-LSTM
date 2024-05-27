# Time-Series-with-LSTM

Time series is a sequence of data points collected over an interval of time. 

![TS](https://github.com/zahraasadi257/Time-Series-with-LSTM/assets/57061013/e2d57cef-ed44-4387-bd62-61debea7d857)



This repository contains ""`LSTMPredictor`"" class is a PyTorch-based neural network module designed for time-series prediction. It employs a dual-layer ""LSTM (Long Short-Term Memory)"" architecture to process sequential data, capturing complex dependencies and temporal patterns. The model is initialized with a hidden state dimensionality, which is configurable via the `n_hidden` parameter. During the forward pass, the network takes an input sequence and optionally predicts future values. The code snippet includes a training loop using the ""LBFGS optimizer"", a robust choice for models with a small number of parameters. 
