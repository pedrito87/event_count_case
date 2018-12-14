# Event count case
The purpose of this case is to find which of the features affect the outcome of the event the most, and to train a model that would succesfully predict the future events. The data is not described in any way, so you are starting from scratch, trying to find what drives the results.

The task reads as follows:

This case asks you to predict the number of events in a dataset, where the event likelihood is a potentially complex function of a large number of other variables. To help you with this task there is an included set of training data, train.csv, which contains 65,536 observations of 10 explanatory variables. The last variable in the dataset, labeled “y”, is a binary target variable representing the occurrence of some event that may depend on any combination of the 10 explanatory variables. The file test.csv contains an additional 65536 observations of the 10 explanatory variables. 
Your task is: 
1) Predict the number of events in the test set 
2) Determine which of the explanatory variables are relevant for solving task 1. Moreover, try to characterize the numerical sensitivity of the event likelihood to the relevant variables (i.e. the weights/coefficients from the model).

You are given two csv files: train and test.
