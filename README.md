# Tesla-Stock-Prediction
Tesla Stock Price Prediction Using LSTM

Project Overview

This project predicts Tesla stock prices using a Long Short-Term Memory (LSTM) neural network.

LSTM is a type of Recurrent Neural Network (RNN) that is useful for time-series data. It learns patterns from previous Tesla stock prices and predicts future stock prices.

Dataset

The dataset used in this project is "Tesla.csv".

The dataset contains historical Tesla stock information such as:

- Date
- Open
- High
- Low
- Close
- Volume

The Close price is used for prediction.

Data Preprocessing

The following steps are performed:

1. Load the dataset using Pandas.
2. Check for missing values.
3. Select the Close price.
4. Scale the data using MinMaxScaler.
5. Create sequences for LSTM.
6. Split the data into training and testing data.

LSTM Model

The LSTM model is built using TensorFlow and Keras.

The model uses:

- LSTM layers to learn time-series patterns.
- Dropout layers to reduce overfitting.
- Dense layer to predict the stock price.

Model Evaluation

The model is evaluated using:

- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

These metrics are used to measure the difference between actual and predicted stock prices.

Results

The project compares the actual Tesla stock prices with the predicted stock prices using a graph.

The model performance is also evaluated using MSE, RMSE, and MAE.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

How to Run

Install the required libraries:

pip install -r requirements.txt

Open Jupyter Notebook:

jupyter notebook

Open:

Tesla_Stock_Prediction.ipynb

Run all the cells from beginning to end.

Make sure "Tesla.csv" is in the same folder as the notebook.

Project Structure

Tesla-Stock-Prediction/
│
├── Tesla_Stock_Prediction.ipynb
├── Tesla.csv
├── README.md
└── requirements.txt

Conclusion

This project demonstrates the use of an LSTM neural network for Tesla stock price prediction. The model learns patterns from historical stock data and predicts stock prices for comparison with actual values.
