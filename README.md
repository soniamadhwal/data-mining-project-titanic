# Predictive Modelling of Titanic Passenger Survival: A Data Mining Approach

Introduction

The objective of this project is to predict the survival of passengers on the RMS Titanic using machine learning algorithms. The analysis uses two datasets: titanic_ticket_data.csv and titanic_personal_data.csv, merged on PassengerId.

Dataset Overview The datasets provide detailed information on 1,204 passengers, including socio-demographic and ticket attributes. Key variables include PassengerId, Survived, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Job, and Salary.

Methods Used Data preprocessing and feature engineering were conducted using the KNIME platform. Techniques included data merging, missing value imputation, and variable categorization. Random Forest and Logistic Regression algorithms were employed for prediction, evaluated using cross-validation and metrics like accuracy, precision, recall, and ROC-AUC.

Data Mining Theory

Logistic Regression Logistic Regression offers a probabilistic interpretation of survival likelihood based on passenger characteristics, suitable for binary classification tasks.

Random Forest Random Forest, an ensemble learning method, improves prediction accuracy by combining multiple decision trees, handling complex interactions and variability well.

Data Exploration and Preparation

Data Exploration Techniques

Key variables such as Survived, Sex, Age, SibSp, Parch, Salary, Fare, and Embarked were explored to understand distributions and relationships.

Data Preprocessing Methods

Handling Missing Data: Imputation and removal strategies for columns with missing values. Feature Selection and Engineering: Age and salary were categorized, and outliers in Fare were handled using IQR.

Experimental Setup

Data Preprocessing

Loading and Merging Data: Merged datasets based on PassengerId. Feature Selection and Engineering: Extracted and categorized variables, imputed missing values, and handled outliers.

Model Training and Validation

Random Forest: Trained and validated using cross-validation with a 10-fold setup. Logistic Regression: Trained and validated similarly, ensuring consistency in preprocessing steps.

Evaluation Methods

Performance metrics included accuracy, precision, recall, F1-score, sensitivity, specificity, and Cohen's kappa.

Results and Discussion

Random Forest Model Results

Performance: Recall of 0.916, precision of 0.866, accuracy of 85.92%, and AUC of 0.895. Interpretation: Effective in capturing complex interactions, superior overall performance.

Logistic Regression Model Results

Performance: Recall of 0.912, precision of 0.862, accuracy of 84.5%, and AUC of 0.872. Interpretation: Provides valuable insights into feature importance, though slightly less effective than Random Forest.

Conclusion and Reflections Random Forest outperformed Logistic Regression in predictive accuracy and handling complex interactions. Logistic Regression, however, offered interpretable feature impacts.

Future Directions

Future work could explore advanced ensemble techniques, deep learning, and integrating qualitative data for enriched analysis, improving the understanding of survival dynamics on the Titanic.
