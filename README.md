# Mobile Price Prediction Project

Welcome to the "Mobile Price Prediction" repository, where we delve into the fascinating world of predictive modeling to forecast mobile phone prices. This project encompasses a comprehensive approach to data preprocessing, model application, and hyperparameter optimization, culminating in the identification of the most effective predictive model.

## Data Preprocessing Overview

Data preprocessing is a critical step in ensuring the accuracy and effectiveness of our models. Our process includes:

1. **Description of Data**: Understanding the structure and type of data we are working with.
2. **Data Information**: Gaining insights into the data, including the number of features and records.
3. **Missing Value Analysis**: Checking for and addressing missing values in the dataset.
4. **Outlier Detection**: Identifying and handling outliers that can skew our model predictions.
5. **Correlation Analysis**: Exploring the relationships between different attributes in the data.
6. **Feature Selection**: Employing SelectKBest for choosing the most significant features for our models.
7. **Data Balancing Check**: Assessing if the dataset is balanced and taking steps to address any imbalance.
8. **Target Correlation**: Identifying the attributes most correlated with the Price Range, our target variable.

## Applied Models

We have applied a range of machine learning models to predict mobile prices accurately:

1. **Logistic Regression**
2. **Decision Tree (Gini Index)**
3. **Random Forest**
4. **K-Nearest Neighbors (KNN)**
5. **Naive Bayes**
6. **Linear Support Vector Machine (LSVM)**
7. **Neural Network**

## Hyperparameter Optimization

To fine-tune our models, we employed the GridSearch algorithm. This approach enabled us to identify the best hyperparameters for each model, enhancing their performance and accuracy.

## Conclusion

After a thorough comparison of the accuracies of all the applied models, we discovered that the Linear Support Vector Machine (LSVM) emerged as the most efficient classifier for this project. This finding underscores the importance of not just model selection but also the fine-tuning of model parameters in predictive analytics.

Thank you for visiting our project. We hope our work inspires and aids in your endeavors in the realm of predictive modeling and machine learning!
