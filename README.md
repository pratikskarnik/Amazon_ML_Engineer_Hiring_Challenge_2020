# Amazon_ML_Engineer_Hiring_Challenge_2020
It is a solution to amazon ml engineer hiring challenge 2020

# Problem Statement
Based on the historical data of a ecommerce website design a classifier to know whether to target the particular user or not and make a presentation proposal for the same.

# Approach
Have used datasets provided in the challenge.
Cleaned data and filled NA values with medians in numerical features and modes in categorical features.
Selected features having correlation coefficients within range -0.5 and 0.5 and done One Hot Encoding for categorical features.
Scaled data and used SVM Classifier to built generalized model having 96% accuracy on train data and 97% accuracy on validation data.
Predicted using the model having 97% precision on validation data.
Model predicted classes using 93.79% precision on test data.

# Score
Got 93.79 score
