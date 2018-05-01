# Forecast Sales

Sales forecasts have traditionally been computed on time series data using regression models, such as linear regression models, with the limitation of only the time-series data as an input. The solution we propose is to utilize a Multi-layer Perceptron neural network to apply a supervised learning approach to forecast monthly sales using more features than just the time-series of sales. We will be using the date for the item-store sale data, monthly mean for the price of the item at each store, monthly total sales for that item for each store, previous month’s total sales for that item at that store, and a TfidfVectorizer of the item categories as input features to the Multi-layer Perceptron. We expect the ability of the Multi-layer Perceptron to utilize more features than just periodic sales to lead to a higher RMSE score than a simple linear regression.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

- Python 3.6
- NumPy
- Pandas
- matplotlib
- sklearn


### Installing

A step by step series of examples that tell you have to get a development env running

- Install Python 3.6 environment with needed packages listed in Prerequistes

## Running the Forecast

- Save sales data as "sales_train.csv" in "data" folder
- Run "sales-forecast-final.ipynb" using "test.csv" stored in "data" folder
- Forecasts for next month's total sales for each store-item combination outputted as "forecast.csv"

## Built With

* [Jupyter](https://jupyter.org/)

## Authors

* **Saad Khan** - *Initial work* - [saadk408](https://github.com/saadk408)

## Acknowledgments

* [Kaggle](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
