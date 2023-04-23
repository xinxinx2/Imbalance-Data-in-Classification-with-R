# Imbalance-Data-in-Classification-with-R
Confusion matrix/ ROC Curve/ Area-under-the-Curve (AUC)

Use the Default data set from library ISLR with information of n = 10000 bank customers. 

It includes the income and the average credit card balance. The response (or target) variable default is a factor with levels No and Yes indicating whether the customer defaulted on their debt. 

We are interested in predicting whether a customer would default the credit card payment using as predictors the customer balance and income, only.


## Overview of Dataset

<img width="411" alt="image" src="https://user-images.githubusercontent.com/108433979/233813773-3251c6c5-677d-48d3-a932-ea03f3647da0.png">


## Use two columns as predictors
<img width="328" alt="image" src="https://user-images.githubusercontent.com/108433979/233813816-e53ec380-c599-452b-b7c9-b2f9ff70662f.png">

## Use set.seed(1) to split the data (50%/50%) into train and test (stratified) sets.

<img width="518" alt="image" src="https://user-images.githubusercontent.com/108433979/233813841-e1881427-3ad6-49d8-be66-828ad0e2cf58.png">

## Use the train set to fit a Logistic regression model (Threshold = 0.08)

In the test set to find
a) True Positive Rate (TPR) and False Positive Rate (FPR).
b) Area under the ROC curve (AUC)

<img width="693" alt="image" src="https://user-images.githubusercontent.com/108433979/233813895-11f8571f-122d-4684-b284-fb9ee5af9c14.png">

## Plot ROC curve
<img width="868" alt="image" src="https://user-images.githubusercontent.com/108433979/233813899-8cd554e5-d6c4-44b5-baf3-3c88c6b0c1ec.png">

## Calculate AUC
<img width="755" alt="image" src="https://user-images.githubusercontent.com/108433979/233813909-c0061f9e-c62f-476a-a387-8eb3a38ff4d8.png">

## Use the train set to fit a Naive Bayes model model (Threshold = 0.08) 
<img width="804" alt="image" src="https://user-images.githubusercontent.com/108433979/233813965-455d2ff3-312c-4ff1-bc55-33c994cef78d.png">

<img width="606" alt="image" src="https://user-images.githubusercontent.com/108433979/233813974-ba0cbac4-7ade-43f1-9b9e-567e5d4df863.png">

## Plot ROC curve
<img width="870" alt="image" src="https://user-images.githubusercontent.com/108433979/233813979-68e91336-6ecb-4a7c-9ba8-e040afbbd9c7.png">

## Calculate AUC
<img width="851" alt="image" src="https://user-images.githubusercontent.com/108433979/233813986-3fa23284-45c1-458b-9503-b1b12c5f1a5a.png">

