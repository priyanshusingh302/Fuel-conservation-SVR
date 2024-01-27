# Fuel-conservation-SVR
This repository hosts the code for a project aimed at reducing fuel usage through Support Vector Regression (SVR) techniques. The project focuses on leveraging SVR models to optimize fuel consumption across various systems or processes, ultimately leading to enhanced efficiency and reduced environmental impact.

## Coal Mine Haulers Fuel Consumption Optimization

This repository contains code and resources for optimizing fuel consumption in coal mine haulers using Support Vector Regression (SVR) techniques.

### Data Description

The data provided is collected from coal mine haulers and includes the following parameters:

- `EMPTY TIME (minutes)`
- `EMPTY STOP TIME (minutes)`
- `QUEUE AT LU (minutes)`
- `WAIT AT LU (minutes)`
- `SPOTTING TIME (minutes)`
- `LOADING TIME (minutes)`
- `HAULING TIME (minutes)`
- `HAULING STOP TIME (minutes)`
- `WAITING TIME @DUMP (minutes)`
- `DUMP TIME (minutes)`
- `LOAD TONS`
- `TOTAL LEAD DISTANCE (KM)`

### SVR Model Performance

The SVR model is trained and evaluated using the following metrics:

#### Training Metrics:
- R-squared: 0.53
- Explained Variation: 0.53
- Mean Squared Error: 276.8
- Root Mean Squared Error (RMSE): 16.64
- Mean Absolute Error (MAE): 8.11

#### Test Metrics:
- R-squared: 0.76
- Explained Variation: 0.77
- Mean Squared Error: 136.55
- RMSE: 11.69
- MAE: 7.62

### Percentage Change in Fuel Consumption

The repository includes calculations for the percentage change in fuel consumption corresponding to 2% and 5% changes in the input parameters.
