# Poisson Regression for Count Data
This project implements Poisson regression to model and predict count data using gradient ascent optimization.

## Overview
Poisson regression is suitable for modeling count data and contingency tables. It assumes the response variable follows a Poisson distribution and is useful for predicting the number of events occurring within a fixed period.

## Features
* Implements Poisson regression using gradient ascent.
* Fits the model to training data and evaluates on validation data.
* Computes evaluation metrics: MSE, MAE, RMSE, Poisson Deviance.
* Visualizes the relationship between true counts and predicted counts.

## Dependencies
* Python 3.x
* NumPy
* Matplotlib
* SciPy

## Data
Place the following data files in a data/ directory:

* data/train_poisson.csv
* data/valid_poisson.csv
