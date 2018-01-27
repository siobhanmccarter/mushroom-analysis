# Mushroom Edibility Analysis

See the data source [here](http://archive.ics.uci.edu/ml/datasets/Mushroom)

See the raw data [here](https://github.com/siobhanmccarter/mushroom-analysis/blob/master/data/agaricus-lepiota.data.csv)

See the full write-up [here](https://github.com/siobhanmccarter/mushroom-analysis/blob/master/report/mushroom_report.ipynb)

See the coding used [here](https://github.com/siobhanmccarter/mushroom-analysis/blob/master/src/mushroom_code.ipynb)

## Goal

This is a project for DSCI 573, a features and model selections class. The goal was to perform a full analysis on a dataset of my choosing. In this case, I chose a dataset pertaining to mushroom edibility. The goal was to create an accurate model that could predict whether or not a mushroom was edible given a set of attributes.

## Data & Project Overview

I used [this dataset](http://archive.ics.uci.edu/ml/datasets/Mushroom) from UCI's machine learning database. It has 22 attributes, all describing characteristics of each mushroom, and a target column labelling that mushroom as either poisonous or edible.

I tested out 3 different classifier models (SVM, decision tree, and random forest). In the end, I chose a linear SVM model, which had a higher initial error. I did this because I wanted to test out how changes in the parameters and number of features would affect the accuracy of the model. It performed incredibly well after my tuning, with a training error of 0.0266 and a test error of 0.0286.

## Running the Analysis

This project is pretty easy to run. Follow these steps:

1. Clone this repo locally

2. Ensure that you have the dependencies installed 

3. Run the code notebook file (seen [here](https://github.com/siobhanmccarter/mushroom-analysis/blob/master/src/mushroom_code.ipynb)) in order 

#### Dependencies

This project used the following:

- Jupyter Notebook `v5.0.0`
- Python `v3.6.1`
- SKLearn `v0.18.1`
- Pandas `v0.20.1`
- Numpy `v1.12.1`
- Matplotlib `v2.0.2`