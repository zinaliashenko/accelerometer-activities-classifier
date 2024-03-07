### Classification of activities using accelerometer data

**Description**
According to the accelerometer data from the mobile phone, it is necessary to classify what kind of activity a person is engaged in: walking, standing, running or climbing stairs. To improve the performance of the algorithms, a dataset is first prepared and time domain characteristics are calculated. You can learn more about these characteristics in the article in the repository.

**Installation**
Install required dependencies: pandas, scikit-learn.
Download the data from the accelerometer and execute the code.

**Data preparation**
Data is loaded from CSV files and then normalized using Min-Max Scaling. The data is then divided into training and test sets.

**Classification models**
Two classification models were used: support vector (SVC) and random forest.

**SVM Linear**
The SVC model with a linear kernel was used to classify the activities. The results of the confusion matrix and the classification report are presented.

**Decision Tree**
The RandomForestClassifier model was used to classify activities. The results of the confusion matrix and the classification report are presented.

**Feature selection**
Feature selection methods are used to improve results. Three different pipelines were used using SelectKBest to extract the best features for SVM and Decision Tree models.

**Author**
Zinaida Liashenko
