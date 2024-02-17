# Stock Price Prediction

## Project Overview
This project focuses on predicting the stock prices of Tata Motors using historical data. The aim is to leverage machine learning techniques to forecast future stock prices based on past trends. This project utilizes Python, specifically the libraries TensorFlow, Keras for building and training the model, and yfinance to fetch historical stock data.

## Features
- **Data Collection**: Utilizes yfinance to fetch historical stock data.
- **Data Processing**: Cleans and preprocesses the data to make it suitable for the machine learning model.
- **Model Building**: Uses a Long Short-Term Memory (LSTM) model, implemented with Keras and TensorFlow, to predict stock prices.
- **Visualization**: Employs Matplotlib to visualize the actual vs. predicted stock prices.

## Technologies Used
- Python
- TensorFlow
- Keras
- yfinance
- Matplotlib
- Jupyter Notebook

## Setup & Installation
Ensure you have Python installed on your system. Then, install the required libraries using the following command:
```bash
pip install tensorflow keras yfinance matplotlib notebook
```

## Usage
To use this project, clone the repository, navigate to the project directory, and open the Jupyter Notebook (.ipynb file) in Jupyter Lab or Jupyter Notebook. Execute the cells in sequence to fetch the data, train the model, and see the predictions.

## Model
The project employs an LSTM model, which is particularly suited for time series forecasting like stock price predictions. LSTM helps in capturing the long-term dependencies in time series data, making it ideal for predicting future stock prices based on historical trends.

## Results
The model's performance is evaluated by comparing the predicted stock prices against the actual stock prices. A line graph visualization shows the effectiveness of the model in forecasting Tata Motors' stock prices.

## Conclusion
This project demonstrates the potential of using LSTM models for stock price prediction. While the model shows promising results, it's important to note that stock market predictions are subject to various unpredictable factors. Hence, this model should be used as a tool among others for making investment decisions.

## License
This project is open-sourced under the MIT License. See the LICENSE file for more details.

