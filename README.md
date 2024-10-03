# recurrent-breast-cancer-detection

## Introduction

This project focuses on detecting recurrent breast cancer using machine learning models. Breast cancer, one of the most prevalent cancers, can become more severe due to its recurrence in patients. The primary goal of this project is to predict whether a patient’s breast cancer is recurrent, leveraging various machine learning techniques for better diagnosis and prognosis.

## Methodology

The proposed methodology is divided into several key stages:

1.	Data Collection and Preprocessing: The dataset used comprises patient data with a wide range of features including cancer cell data, tumor information, and secondary health complications like brain tumors, pancreatic cancer, and heart arrhythmias. The data was cleaned by handling missing values and encoding categorical data for machine learning models.
	2.	Feature Engineering: Features were analyzed and selected based on their significance in predicting cancer recurrence. This step also included splitting the dataset into training and test sets.
	3.	Model Selection: Several machine learning models were applied including Adaboost, XGBoost, and Histogram Gradient Boosting Classifier. The Voting Classifier, an ensemble model combining the predictions of multiple models, was selected for final implementation due to its high accuracy.
	4.	Training and Evaluation: The models were trained using the processed dataset, and their performance was evaluated using various metrics like accuracy, precision, recall, and F1-score. The Voting Classifier achieved the best results with an accuracy of 98.24%, precision of 0.9782, recall of 0.962, and F1-score of 0.969.

## Conclusion

The project successfully developed a robust model for predicting recurrent breast cancer with high accuracy. The Voting Classifier model proved to be effective for this purpose, demonstrating its potential in medical diagnostics. Future work could extend this model to predict additional cancer-related complications and integrate gene mutation analysis to further enhance the accuracy of recurrence predictions.
