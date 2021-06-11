# Machine-Learning-Assignment
Resampling
Use the imbalanced learn library to resample the LendingClub data and build and evaluate logistic regression classifiers using the resampled data.
To begin:


Read the CSV into a DataFrame.


Split the data into Training and Testing sets.


Scale the training and testing data using the StandardScaler from sklearn.preprocessing.


Use the provided code to run a Simple Logistic Regression:

Fit the logistic regression classifier.
Calculate the balanced accuracy score.
Display the confusion matrix.
Print the imbalanced classification report.



Next you will:


Oversample the data using the Naive Random Oversampler and SMOTE algorithms.


Undersample the data using the Cluster Centroids algorithm.


Over- and undersample using a combination SMOTEENN algorithm.


For each of the above, you will need to:


Train a logistic regression classifier from sklearn.linear_model using the resampled data.


Calculate the balanced accuracy score from sklearn.metrics.


Display the confusion matrix from sklearn.metrics.


Print the imbalanced classification report from imblearn.metrics.


Use the above to answer the following questions:

Which model had the best balanced accuracy score?




Which model had the best recall score?




Which model had the best geometric mean score?


Ensemble Learning
In this section, you will train and compare two different ensemble classifiers to predict loan risk and evaluate each model. You will use the Balanced Random Forest Classifier and the Easy Ensemble Classifier. Refer to the documentation for each of these to read about the models and see examples of the code.
To begin:


Read the data into a DataFrame using the provided starter code.


Split the data into training and testing sets.


Scale the training and testing data using the StandardScaler from sklearn.preprocessing.


Then, complete the following steps for each model:


Train the model using the quarterly data from LendingClub provided in the Resource folder.


Calculate the balanced accuracy score from sklearn.metrics.


Display the confusion matrix from sklearn.metrics.


Generate a classification report using the imbalanced_classification_report from imbalanced learn.


For the balanced random forest classifier only, print the feature importance sorted in descending order (most important feature to least important) along with the feature score.


Use the above to answer the following questions:


Which model had the best balanced accuracy score?


Which model had the best recall score?


Which model had the best geometric mean score?


What are the top three features?


