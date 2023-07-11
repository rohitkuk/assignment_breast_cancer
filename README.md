# Assignment Breast Cancer Wisconsin

I have chose Breast Cancer Wisconsin problem statement for this assignment, reason being I have been previously worked for cancer detection company hence it is more relevant and sensible to me.

For the Approach as the assignment states I have to build a deep learning model so I have used PyTorch for creating  Neural Network I have mentioned the steps to my approach below.

For Evaluation I have used Accuracy as a primary metric but in the notebook I am outputting the classification report which has precision, recall as well as F1 Score.

I also wanted to monitor AUC scores.

The Entire Code is divided in to Steps listed below with explanation

## Initial Setup

This setup is majorly just setting things up

- Importing Modules
- Reading Data
- Some plot functions
- Seeding Everything for reproducing the results

## EDA

Second Step is Basic EDA to understand data and classes

- Basic info about Datatypes
- Describing the df to understand ranges and distributions
- class Balancing
- corelation map

## Preprocessing

- Removing Unwanted Columns
- checking if Null Values
- Preparing the class labels

## Hyper Parameter

- Defining basic Model Parameter

## Dataset Prepration

- Splitting
- Normalising
- Loading

# Model Architecture

- Defining the ANN
- Early Stooping
- Train , Val and Test Functions

# Training Loop

- Training Process
- Plots
- Accuracy Report

## WHAT ELSE CAN TRY

- Accuracy is a good metric but can also get AUC scores to get better understanding.
- can compare with Classic Machine Learning Approaches like XGboost.
