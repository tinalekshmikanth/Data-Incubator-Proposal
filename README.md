Data-Incubator-Project Proposal

Project Title: Wellness prediction from Food Access

The project aims to predict the relative health importance index (RHSI) of each county from the food access data set from Food Environment Atlas.
Aim of project is to build a model to predict the RHSI of non communicable diseases in each county.
The Food Environment Atlas data set will be merged with RHSI Index from CHSI dataset.

Data Preparation

Data cleaning and final dataset will be preapared by merging columns from CHSI data set and he Food Environment Atlas data set 
with target variable (RHSI index) and feature selection will be performed.

Data Analysis

Exploratory Data Analysis will be done using clustering techniques to study the data and find patterns within. K means 
clustering techniques will be used as the unsupervised learning algorithm. This algorithm is expected to produce clusters wich can be 
studied.

Perform maximal correlation analysis on variables.

Use ANOVA and tukeys test to find variable significance.

Model Building

Step 1

Model Building - As a classification Problem 

Use  RHSI - Colon Cancer (chosen since Colon Cancers could have high correlation with variables) to  define Threshold  
and create taget variable as  1 and 0 which indicates high health importance index and low health importance index 
and optimize model for accuracy.

Algorithms: Random Forest and Logistic Regression.


Step 2 

Model Building - As a Regression  Problem 

Use RHSI - Colon Cancer as a target variable and train the model to predict RHSI.

Algorithms: Feed forward Neural Network


Future Work

Twitter analysis on various areas have proved that results from twitter analysis have strong correlation with those from
Health Statistics. Future work of the project will be to anlayze the tweets and predict the RHSI.









