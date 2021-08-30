# House-Price-Prediction
A linear regression model to predict house prices based on existing features.

## Installation and Setup
```
git clone https://github.com/whoparthgarg/House-Price-Prediction
```

## Data-set Examination 
The data-set in CSV format is shown below:
<center><img src="assets/dataset.png" alt="logo"></center>

* The training data-set has 3000 samples, 5 features and 1 target variable.
* The test data-set has 2000 samples and 5 features.
* The target variable is the price.

The data-set is available here:
https://github.com/whoparthgarg/House-Price-Prediction/blob/main/USA_Housing.csv

## Exploratory Data Analysis
<center><img src="assets/eda_1.png" alt="logo"></center>
<center><img src="assets/eda_2.png" alt="logo"></center>
<center><img src="assets/eda_3.png" alt="logo"></center>

## Model Evaluation
<center><img src="assets/model_evaluation.png" alt="logo"></center>

Interpreting the coefficients:

* All features fixed, a 1 unit increase in Avg. Area Income is associated with an increase of \$21.52 .
* All features fixed, a 1 unit increase in Avg. Area House Age is associated with an increase of \$164883.28 .
* All features fixed, a 1 unit increase in Avg. Area Number of Rooms is associated with an increase of \$122368.67 .
* All features fixed, a 1 unit increase in Avg. Area Number of Bedrooms is associated with an increase of \$2233.80 .
* All features fixed, a 1 unit increase in Area Population is associated with an increase of \$15.15 .

## Predictions
<center><img src="assets/predictions.png" alt="logo"></center>

## Residual Histogram
<center><img src="assets/residual_histogram.png" alt="logo"></center>

## Regression Evaluation Metrics
<center><img src="assets/metrics.png" alt="logo"></center>