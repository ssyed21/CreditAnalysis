# CreditAnalysis
The purpose of this code is to predict credit risk and use machine learning to look for credit card risk. The program evaluates the performance of the machine learning models.
# Results
## Oversample
### Naive Random Oversampling:
- balanced accuracy score = 0.6456130066757718
- recall score = 0.68
- geometric mean score = 0.64
### SMOTE Oversampling
- balanced accuracy score = 0.6234433606890912
- recall score = 0.64
- geometric mean score = 0.62
## Undersample
### Cluster Centroids algorithm
- balanced accuracy score = 0.5293026900499977
- recall score = 0.45
- geometric mean score = 0.52
## Combination (Over and Under) Sampling
### SMOTEENN
- balanced accuracy score = 0.6156536172852936
- recall score = 0.54
- geometric mean score = 0.61
## Ensemble Learners
### Balanced Random Forest Classifier
- balanced accuracy score = 0.67209249388625
- recall score = 1.00
- geometric mean score = 0.59
### Easy Ensemble AdaBoost Classifier
- balanced accuracy score = 0.9345627309023371
- recall score = 0.95
- geometric mean score = 0.93
# Summary
With the exception of Easy Ensemble AdaBoost Classifier, none of the models had any high accuracy scores. Based off the high scores from the Easy Ensemble Ada
Boost Classifier I would recommend this model to be used for predictions.
