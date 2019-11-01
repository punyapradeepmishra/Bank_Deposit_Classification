# Bank_Deposit_Classification
Given a dataset of socio-demographic and call details, we would like to predict whether customers will make a deposit at the bank or not. We would like to take a systematic approach by analyzing the social factors at play.
Ran the below algorithms and discovered that Boosting recorded the highest accuracy. Due to the lower cost of telephone services, in modern age, we do not consider a cost matrix in calculating misclassification costs. However, we see that Boosting has greater sensitivity and high enough specificity to identify who may place deposits. Boosting would be more valuable than other models in predicting deposits when they were actually made.
Method                Accuracy%  Sensitivity% Specificity%  
Neural Networks         88.35      4.72         99.33
Logistic Regression     88.38      8.8          98.8
Random Forest           88.39      0            100
