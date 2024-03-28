# Energy Forecasting Using a LSTM Neural Network

## Project Overview
Based on data from a relatively long window of time, what will the next month look like? Using data on the amount of energy generated and demanded in the Lower 48 Region collected from the U.S. Energy Information Administration's API, that was the question asked. The time-series data ranged from January 1, 2019 to December 31, 2023 with daily frequency.

A variety of potential methods exist for forecasting time-series data, but for this project a Long Short-Term Memory (LSTM) neural network model was used. As a type of recurrent neural network, information is kept from earlier inputs of a sequence and affects the output of later elements. When the order of data is important to determine future outputs like it can be with time-series data, this ability to remember information from prior points is incredibly useful.
