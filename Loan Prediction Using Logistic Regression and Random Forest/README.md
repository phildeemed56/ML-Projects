**Loan Approval Prediction Project**

**Introduction**

Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan. 


Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.


This is a standard supervised classification task. A classification problem where we have to predict whether a loan would be approved or not. Below is the dataset attributes with description.


**Dataset**

The dataset used for this project contains various attributes such as Gender, Marital Status, Education, Income, Loan Amount, Credit History, and Loan Status (Approved or Denied). The dataset is stored in a CSV file named

Dataset Link: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset


**Project Structure**

The project consists of the following components:

Data Preprocessing:

Loading and exploring the dataset using pandas.
Handling missing values by imputing them with appropriate statistics (mean, mode) for numerical and categorical attributes.

Exploratory Data Analysis (EDA) to understand the distribution and relationships between variables.


Model Training:

Implementing machine learning models such as Logistic Regression, Decision Trees, Random Forests, and ExtraTreesClassifier for loan prediction.

Evaluating model performance using accuracy metrics and cross-validation.

Hyperparameter Tuning:

Fine-tuning the Random Forest model by adjusting hyperparameters such as the number of estimators, minimum samples split, maximum depth, and maximum features.
Model Evaluation:

Assessing model performance using confusion matrices to understand prediction outcomes (True Positive, True Negative, False Positive, False Negative).
GitHub Repository:


**Contributing**

Contributions to this project are welcome. If you have any suggestions for improvement or feature requests, please open an issue or submit a pull request.
