# Red Wine Quality Analysis
The Red and White Wine Quality data sets are available in UCI. Please refer to the abstract, problem statement and data sets description at https://archive.ics.uci.edu/ml/datasets/Wine+Quality. Each data set contain 12 features including quality as the target variable.

## Notebook Abstract
In this notebook, we have considered only the Red Wine quality data set.

In the problem statement, the authors state "we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods."

Accordingly, we have attempted to determine the accuracy of predictions using different subsets of the features. We have developed four Machine Learning Models and compared the accuracy of predictions resulting from each model. For each ML technique, we have considered (a) the complete set of 11 features (b) dropped 3 features that show very weak correlation i.e., 0.0-0.20 and (c) dropped an additional 5 features exhibiting weak correlation i.e., 0.20-0.40 with the target. In short 12 models have been developed.

We find that predictions using Linear Regression exhibit the best accuracy of about 92% even with just three features. This may be due to the 'privacy and logistics issues' mentioned by the data set authors.

Predictions made using Logistic Regression, Decision Tree and Random Forest yield poor accuracy between 50-70% even when K-fold and Grid Search CV methods are used to improve the predictions.
