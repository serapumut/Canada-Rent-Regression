# Canada-Rent-Regression
In this project, I will work with a dataset containing rental prices for units in across Canada in 2024.
Dataset obtained from rentfaster.ca. 
The data dictionary can be found here.
My goal is to explore multiple regression models, in order to find a model that predicts the rental price most accurately.
I’m starting to project by loading packages and dataset.
After finding and cleaning missing values, I checked each columns' unique values. In this way, I got clean and useable data by dropping some columns. 
I used visualization to identify the patterns. 
I did Linear Regression, Polynomial Regression, Ridge and Lasso Regression respectively.
Then I did Cross Validation. 
According to Cross Validation results, The MAE, MSE, and RMSE from the test set are slightly higher than the values from cross-validation, which is expected as the model is now being evaluated on unseen data. This indicates that the model is generalizing fairly well.
As a conclusion, ridge regression model performs reasonably well with the current parameters. The results are consistent, showing that the model can predict rental prices with an acceptable level of accuracy.
