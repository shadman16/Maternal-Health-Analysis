# Maternal-Health-Analysis
## Reasoning Behind Choosing The Dataset
In Bangladesh there are a lot of birth related complicacies that occur in the rural level. Due to the socio economical state of the family, infrastructure and lack of proper access to health care, the country sees around 173 maternal deaths per 100,000 live births in Bangladesh as seen in World Bank Data. Thus we are falling behind from the SDG Goal of reducing the global maternal mortality ratio to 70 deaths per 100,000 live births by 2030. My focus was to find a dataset that generated from the rural areas of Bangladesh, where the variables can be used to group expecting mothers in different risk clusters. This preliminary analysis can be a gateway to create a model that can be used to classify a particular woman in different cluster so that we can decide who should get extra care during the pregancy period thus reducing the chance of mortality during child birth. The Dataset was obtained from the Machine Learning Data Repository of UCI titled Maternal Health Risk Data Set Data Set.The Data has been collected from different hospitals, community clinics, maternal health cares from the rural areas of Bangladesh through the IoT based risk monitoring system.

## The Problem Goal : Categorizing expecting mothers in Different Risk Clusters

The goal of this notebook analysis is to do some preliminary data analysis to understand the data(Null Value/Class Imbalance etc.), Data Visualization to get insights and Lastly preparing the data for Logistic Regression taught in our course and lastly using scikit-learn's own logistic regression library to cluster the sample data points.

## Dataset Description
Attribute Information:

Age: Any ages in years when a women during pregnant.
SystolicBP: Upper value of Blood Pressure in mmHg, another significant attribute during pregnancy.
DiastolicBP: Lower value of Blood Pressure in mmHg, another significant attribute during pregnancy.
BS: Blood glucose levels is in terms of a molar concentration, mmol/L.
HeartRate: A normal resting heart rate in beats per minute.
Risk Level: Predicted Risk Intensity Level during pregnancy considering the previous attribute.

## Target Goal 
Seperate the sample size from high risk to low risk using logistic regression
