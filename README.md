# ANN Classification model to predict the Customer Churn
 
This repository contains code for predicting customer churn using an Artificial Neural Network (ANN).

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
3. [Methodology](#methodology)
    - [Data Collection](#data-collection)
    - [Exploratory-Data-Analysis-(EDA)](#exploratory-data-analysis)
    - [Data-Preprocessing](#data-preprocessing)
    - [Splitting-Data](#splitting-data)
    - [Model-Building](#model-building)
    - [Model-Training](#model-training)
    - [Model-Evaluation](#model-evaluation)
4. [Results](#results)

## Introduction
Customer churn prediction using an ANN. The code includes data preprocessing, model training, and evaluation.

## Getting Started
### Prerequisites
- Python 3
- Jupyter Notebook (optional)

### Installation
1. Clone the repository.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
'''
## Methodology
 The methodology of a project involves the step-by-step approach you take to solve a problem or achieve a goal. In the context of your churn prediction project using an Artificial Neural Network (ANN), here's a high-level methodology:

## Data-Collection:
Gather the data required for your project. Here the specified dataset contains information about customers, including features like credit score, geography, gender, age, tenure, balance, and more.

## Exploratory-Data-Analysis:
Explore and analyze the dataset to understand its characteristics. This involves:
+ Checking for missing values
+ Handling duplicates
+ Visualizing distributions of variables
+ Exploring relationships between variables

The EDA process helps you gain insights into the data and make informed decisions about preprocessing steps.

## Data-Preprocessing:

Clean and prepare the data for modeling. Steps may include:
+ Removing null values
+ Dropping unnecessary columns (e.g., RowNumber, CustomerId, Surname)
+ Handling duplicate records
+ Label encoding categorical variables
+ Standardizing numerical features

## Splitting-Data:

Divide the dataset into training and testing sets. The training set is used to train the ANN, while the testing set is used to evaluate its performance.


## Model-Building:

Construct an Artificial Neural Network for predicting customer churn. Design the architecture of the neural network, including the number of layers, activation functions, and neurons. In your case, you've used a sequential model with layers of dense neurons.

## Model-Training:

Train the ANN using the training set. Adjust model hyperparameters such as the number of epochs, batch size, and learning rate. Monitor the training process and check for overfitting or underfitting.
## Model-Evaluation:

Evaluate the trained model using the testing set. Calculate metrics such as accuracy, precision, recall, and F1-score. Generate a confusion matrix and a classification report to assess the model's performance.

# Results
Achieved an impressive accuracy of 84.15% with the developed Artificial Neural Network (ANN) model, showcasing the effectiveness of the predictive model in customer churn prediction
