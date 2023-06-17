# Project-1
This is  Machine Learning based Logistic Regression Model Project for predicting the chances of Heart Disease a patient can have based on following factors:
age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal
target represent the case 0 and 1:
case 0 implies that the patient do not have any heart disease
case 1 implies that the patient have a heart disease

Notes:
If the dataset has NULL value, the following measures are suitable to avoid NULL character:
Impute the NaN value with Mean/Median/Mode value.
#dataframe.fillna(df.mean(), inplace=True)
