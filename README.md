# Predict-Flight-Delay
Build a machine-learning model based on historical data. The model should be able to predict the delay and accuracy of the prediction (within the tolerance limit). Also included in the model are those variables that can be captured and measured, prior to flight take off.
Predict Flight Delay

Dataset: Dataset downloaded from the Bureau of Transportation Statistics. Time-period of the dataset was between June-2017 to May-2018. Total 109 columns were there in the dataset.


Methodology: Out of 109 columns, 53 columns had more than 80% data missing, so I had removed those columns. After cleaning the data, Exploratory Data Analysis was carried out. Due to the large dataset, I had chosen the test size as 60% for the model building. I started with the Logistic regression model which gave the accuracy of train and test data as 87% and 88% respectively. As my input variables were continuous, therefore used the Gaussian naïve Bayes to increase the model accuracy.


Key Findings: Based on the carrier wise delay, Southwest has the highest delay followed by American Airlines. Friday shows a uniform delay pattern across all carriers. Cases where the origin and destination city are same (ex: Atlanta), highest delayed is shown by carrier Delta Airlines followed by American Airlines. After running different models, Naïve Bayes was giving good results compared to others. Training data-set’s Accuracy, Precision and Recall were ~95%,~99% and ~75% respectively and on testing dataset, Accuracy, Precision and Recall were ~95%,~99% and ~75% respectively.


Tools and Skills: Logistic Regression, Naïve Bayes and Python.
