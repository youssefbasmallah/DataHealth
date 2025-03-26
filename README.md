# DataHealth - Medical Consultation Prediction Project

Project Overview
--

The primary goal of this project is to predict the number of medical consultations in the United States based on 15 different variables.

Our Approach
--

## Initial Modeling

We began by implementing several machine learning models to predict the target value. However, the initial results were not satisfactory:

- Accuracy was barely above fifty percent.
- F1-scores and confusion matrices indicated poor performance.

## Identifying Challenges

We identified several reasons for these low results:

- **Imbalanced Dataset** : The classes in our dataset were not evenly distributed.
- **Multiclass Classification** : Predicting multiple classes added complexity to the model.

## Data Analysis and Refinement

To address these challenges, we conducted statistical analyses and visualized the data to gain better insights. Our steps included:

1. **Feature Selection** : We removed variables deemed "useless" based on our analysis and retrained the models with the updated dataset.
2. **Qualitative Prediction**: We focused on qualitatively predicting the target variable to improve model performance.

## Limitations

Data Augmentation Issues: We encountered problems with data augmentation as the SMOTE (Synthetic Minority Over-sampling Technique) did not work effectively for our dataset.
