# Credit Risk Prediction Project

## Overview
This project focuses on predicting credit default risk for customers using a dataset containing various attributes such as demographics, financial indicators, employment details, and lifestyle factors. The goal is to determine whether a customer represents a high (1) or low (0) risk of default, aiding the bank's decision-making process for issuing credit cards.

## Dataset Description & Tasks
The dataset comprises the following columns:
- **ID**: Unique identifier for each individual.
- **Gender**: Binary indicator (0 for Female, 1 for Male).
- **Own_car**: Ownership of a car.
- **Own_property**: Ownership of property.
- **Work_phone**: Presence of a work phone.
- **Phone**: Ownership of a personal phone.
- **Email**: Existence of an email.
- **Unemployed**: Current employment status.
- **Num_children**: Number of children in the family.
- **Num_family**: Total family members.
- **Account_length**: Years since the account has been open.
- **Total_income**: Total income of the individual.
- **Age**: Age of the person.
- **Years_employed**: Total years of employment.
- **Income_type**: Source of income.
- **Education_type**: Highest education level attained.
- **Family_status**: Relationship status.
- **Housing_type**: Type of housing.
- **Occupation_type**: Type of work.
- **Target**: Binary classification indicating high (1) or low (0) risk of default.

## Workflow and Methodology
1. **Data Preprocessing**: Cleaned data, handled missing values, and performed outlier removal.
2. **Feature Engineering**: Addressed multicollinearity, encoded categorical columns, and labeled data appropriately.
3. **Exploratory Data Analysis (EDA)**: Explored relationships between variables, identifying key factors affecting credit risk.
4. **Modeling Approach**: Initially utilized Logistic Regression using all variables, followed by iterative model refinement.
5. **Performance Metrics**: Evaluated model performance using various metrics, including accuracy, precision, recall, and F1-score.
6. **Imbalanced Dataset Handling**: Addressed challenges posed by the imbalanced dataset to improve model training and performance.
7. **Visualization**: Presented ROC Curve to illustrate model performance graphically.

## Conclusion and Future Work
The initial model exhibited challenges due to the imbalanced dataset, impacting its ability to generalize well. To be continued, additional steps might include exploring advanced techniques like resampling methods (such as SMOTE), employing ensemble methods, or trying other classifiers to enhance predictive accuracy.

## Tools Used
- Python (Pandas, NumPy, Scikit-learn) for data preprocessing, modeling, and evaluation.
- Matplotlib and Seaborn for data visualization.

*Note: This project is aimed at demonstrating the predictive modeling process for credit risk assessment using machine learning algorithms.*
