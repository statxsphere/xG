## An Expected Goals Model for 5-a-side Football.

### Predicting the probability of a shot turning into a goal.


I used a logistic regression machine learning model using scikit-learn, pandas, numpy, seaborn and matplotlib to predict probability of a given shot from 5-a-side turning into a goal based on variables collected along with the shot.

### Objectives

* Use Machine Learning to come up with a derivative stat - expected goals (xG).
* Understand the variables behind shots and what variables play the largest role in influencing shot outcomes.
* Understand further applications of this statistic.

### Data

The data has all been manually collected during an internship with a Sports Analytics startup. I have then written and executed an algorithm to extract shots and passes over multiple match files, to create the preliminary dataset for modelling. 

### Environment

1. Jupyter Notebook
2. Os
3. Numpy
4. Pandas
5. Seaborn
6. Matplotlib
7. Scikit-learn
8. XGBoost
9. Glob

I compared Logistic Regression, Random Forest and XGBoost.
Logistic was the winner with a training accuracy of 90 % and test accuracy of 84.2%.

### Areas of Improvement

1. Dataset - the dataset was restricted as my NDA allows me to only use limited data and not the entire dataset for model building, however the model showed success on the complete dataset too.
2.  Modelling - We could ensemble models together to try improving accuracy.
3. Data collection - Additional datapoints can be collected to lead to better predictions. For eg: the number of players between shot and goal is generally used in various other xG models.
