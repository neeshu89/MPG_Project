# MPG_Project

## Domain
This problem is drawn from the Auto_MPG dataset from the UCI Machine Learning Database.

This data set has in the past been used to predict the MPG of a vehicle given a number of factors, including weight, model year, and origin.

## Problem Statement
For a single car, given knowledge about other attributes of the car, we will be able to use supervised learning to develop a regression model that can predict the MPG of a car

We will be particularly interested in understanding the association between `mpg` with `weight` and `model year`, while also taking into account the `origin` of the vehicle

## Dataset and inputs
The dataset to be examined contains 9 vehicle specs for 398 vehicles model-year 1970-1982 across 3 geographies.


## Solution Statement
A solution to this problem will be a regression model such as a linear regression, a decision tree regressor, or a support vector regressor.


## Benchmark Model
Given that we seek a regression model, we will use the mean or median of the mpg as a good naive benchmark.


## Performance Metric
Given that this is a regression task, we can measure the success of our model using the $R^2$ metric, the Mean Absolute Error, or the Mean Squared Error.