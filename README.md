# Predicting-University-Admissions
**Task Details**

Using the supplied predictive variables (GRE score, TOEFL score, University Rating, etc) to predict the likelihood of admission of a new candidate.

**Evaluation Criteria**

The best model should be the one that evaluates to have the lowest RMSE overall, and please indicate the error you get on validation set containing the last 100 observations.

[Here is a link to the dataset](https://www.kaggle.com/mohansacharya/graduate-admissions/tasks?taskId=6)

**Work Flow**
we first created several EDA notebooks and tried to carry out feature selection of the predictors, by carrying out a backward elimination process to determine the weight of coefficients.

Based on the analysis from the EDA several Linear and Tree based models were created, and the best performing mopdel on the test data was selected.

The selection criteria was based on the lowest RMSE score obtained from the test data.

After much consideraion the ANN model had the best performance of approximately 0.04. 
