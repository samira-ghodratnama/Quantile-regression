# Quantile Regression for Uncertainty Estimation of Household Expenses

## Problem Statement
The goal of this project is to use Machine Learning to estimate the uncertainty distribution of a household's total monthly expenses as precisely as possible. The dataset includes features such as consumer id, year, month, education level, age of the reference person, family size, urban residency, race, region of residency, state of residency, marital status, occupation, annual income, and consumer unit weight. The target variable is the monthly expense column.

## Dataset
The dataset includes various features at the individual level (such as age, education, race, and income) and the household level (total expenses). The consumer unit weight indicates how representative a row is of the US population. 

## Evaluation Metric
The evaluation metric for this project is Pinball Loss function.

## Project Steps
The project can be broadly divided into the following steps:

### Exploratory Analysis
- Analysing Data Metrics
- Analysing target variable distribution
- Analysis of Feature Interrelations

### Preprocessing Data
- Handling missing values
- Standardizing Variables
- Handling Categorical and Ordinal Features

### Quantile Regression
- Approach1: Quantile Regression via Statsmodels Library
- Approach2: Gradient Boosting Regressor
- Approach3: Deep-learning based approach
- Approach4: Variational Autoencoders

