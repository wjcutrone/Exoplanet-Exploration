# Exoplanet Exploration
The objective of this project was to utilize a machine learning model to classify exoplanets from a dataset. In the project, four different types of machine learning models were tested with the data. The types of machine learning models tested were logicstic regression, a decision tree classifier, k nearest neighbors (KNN), and a support vector machine. All of the models came were imported from Scikit Learn. After testing each of the four models, the model that ended up being the most successful was the decision tree model. However, the logistic regression model was a very close second, with the decision tree's score narrowly edging out those of logistic regression. The decision tree model ended up having the highest r2 score all out of all the models (0.89). It also had the highest scores for macro and weighted average as well (0.87 and 0.90 respectively). Furthermore, for the confirmed planets, it had a higher value for the scores of precision, recall and f1-score (0.80, 0.87, and 0.83 respectively). A copy of the model as well as the jupyter notebook that contains the coding used to build the model can be found in the "best_model" folder.

Model Stats

1) Logistic Regression Model
	- R2 Score: 0.88
	- 
2) Decision Tree Model
	- R2 Score: 0.89
	- 
3) KNN Model
	- R2 Score: 0.83
	
4) SVC
	- R2 Score: 0.50