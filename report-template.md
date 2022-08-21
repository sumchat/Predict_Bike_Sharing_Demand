# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Suman Chatterjee

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Initially I was not able to submit the prediction because I did not agree to the rules of the competition. So I had to go to the Kaggle website and agree to the rules of the competition. Since I am using Windows environment in local machine I had to set up the environment correctly by installing the Kaggle client. Also since Kaggle doesn't accept values which are less than 0 the negative values need to be converted to 0 before submission.

### What was the top ranked model that performed?
TODO: Weighted Ensemble L3 is the model that performed best. Its performance improved after using additional features of date, month and year.
## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: It found the distribution of different variables like temperature, windspeed, humidity. The windspeed data is not normal and is skewed.Also found the weather, working day, season, holiday are categorical variables.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Adding new features improved the model significantly than even tuning the parameters because bikesharing is more dependent on the day, time and hour. So in this case feature selection is more important.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: The model performed a little better after trying different hyperparameters but not better like when we add new features.

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I would spend more time in feature selection and then on trying how to change different hyperparameters.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.



### Create a line plot showing the top model score for the three (or more) training runs during the project.


### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.


## Summary
So from the above we found that feature engineering is the most important aspect of training a model. We need to explore the dataset, find the important variables and add new variables and remove variables that are not necessary.
