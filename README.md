# Energy Consumption Prediction using Machine Learning

This repository contains code and data for predicting building energy consumption using machine learning techniques. The study explores various algorithms and feature engineering techniques to forecast energy usage accurately.

## Dataset
The dataset used in this study is provided by ASHRAE and contains information about building characteristics, meter readings, weather data, and more. You can download the dataset from [this link](https://www.kaggle.com/c/ashrae-energy-prediction/data).

## Methodology
The methodology employed in this study consists of several key steps:
1. **Data Pre-processing:** Raw data is cleaned, missing values are handled, outliers are managed, and data is normalized for analysis.
2. **Feature Engineering:** New features are created to better capture the relationship between input factors and building energy usage. Dimensionality reduction techniques are applied as well.
3. **Modeling:** Ten different machine learning algorithms are used for prediction, including Linear Regression, Decision Trees, and more.
4. **Evaluation:** Model performance is assessed using the root mean squared error (RMSE) metric on training and testing data.

## Observation
### Comparison of Machine Learning Models:
- Decision Tree Regressor performed the best with an RMSLE score of approximately 0.6.
- Linear models showed comparable performance.
- Neural Network model performed the worst, indicating that complexity doesn't always improve predictions.

### Attribute Importance:
- Square footage of the building and building ID were found to be the most significant predictors.
- Time and date-related attributes had lesser impact on energy consumption.

## Results
The Decision Tree Regressor was identified as the most effective algorithm with an RMSLE of 0.6, suggesting close alignment between predicted and actual energy usage. Feature engineering significantly contributed to model accuracy.

## Conclusion
Decision tree-based models are effective for predicting building energy usage. However, due to computational limitations, more advanced models like Random Forest and XGBoost were not tested. Future research could explore these models for further accuracy enhancements.

For code implementation and further details, please refer to the files in this repository.
