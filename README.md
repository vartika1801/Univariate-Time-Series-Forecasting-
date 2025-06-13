# Univariate Time Series Forecasting using LSTM

This repository demonstrates how to implement **univariate time series forecasting** using Long Short-Term Memory (LSTM) neural networks with Keras and TensorFlow.

The goal is to predict the next 10 values in a sequence based on a sliding window of 3 previous time steps. This is a great starting point for learning sequence modeling and applying LSTM to real-world time series problems.

---

## Model Summary

- **Model:** Two stacked LSTM layers with ReLU activation
- **Input:** 3 time steps of univariate data
- **Output:** Forecast for the next value
- **Data:** Manually defined numerical time series
- **Goal:** Predict the next 10 values after the input sequence

---

## Files

| File | Description |
|------|-------------|
| `univariate_lstm.py` | Core script to prepare data, train the LSTM model, and make predictions |
| `README.md` | Project documentation |

---

## Getting Started

### Requirements

- Python 3.7 or higher
- TensorFlow
- NumPy
- Matplotlib

Install dependencies with:

```bash
pip install tensorflow numpy matplotlib

---

### Running the Code

To train the model and generate forecasts, run:

```bash
python univariate_lstm.py

---

### Output
0 day input [196. 210. 223.7]
0 day output [[234.1]]
1 day input [210. 223.7 234.1]
1 day output [[245.6]]
...

