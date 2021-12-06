# Hospital-Readmission-Prediction

This project contains the hospital readmission data prediction for diabetes patiensts. 

Data - https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

We preidct the patient whether they will be coming for readmission or not. 

Models Used - 
1. Decision Tree
2. Random Forest. 
3. Logistic Regression 

The data is highly skewed for patients with readmission so to handle this I have used RandomUnderSampler to reduce the data of majority class.

The best model found was Decision Tree with high recall value. 
