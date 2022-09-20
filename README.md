# Heart_Disease_predictor
A dive into understanding features driving the risk of heart disease by developing
machine learning models

Goal: To detect patterns in respondents' health conditions that could lead to heart disease

**Exploratory Data Analysis Summary**
* The classes are imbalanced in this dataset; less than 10% of the entire dataset have the
dependent variable ‘Heart Disease’ labeled as ”yes”
* There is no missing data; all the rows and columns have a valid entry
* The distributions of patients across features with and without heart diseases are similar
* There is no significant correlation between the continuous variables

**Class Imbalance and it’s problems**
* 10% of sample contains the target class
* This presents problems as we do not have enough data
to explain the variance/ drivers for heart disease
* If we don’t account for class imbalance, we get sub
standard models* with poor predictive power

**What can we do to account for class imbalance?**
* **Cost Sensitive Learning** : Penalizes the cost function by class weight,i.e., misclassification of minority class costs more
* **Sampling Methods** : Synthetically adjusting the class imbalance by increasing the minority class (oversampling) and reducing the majority class (under sampling)

Modelling:
Logistic Regression
Decision Trees
AdaBoost
XG Boost
Random Forest Classification

The above models were performed. Performance metrics like AUC, recall, accuracy, Precision across models were compared. Logistic regression had a better AUC and Recall score which is why we have selected it for prediction.




