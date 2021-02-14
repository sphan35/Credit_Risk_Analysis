# Credit_Risk_Analysis

# Overview of the Credit Risk Analysis

- The purpose of this analysis was utilizing all the data preparation, statistical reasoning, and machine learning skills learned in the module and applying it towards a real-world case of determining credit card risk. Using the credit card risk data set, algorithms such as RandomOverSampler and SMOTE were utilized to oversample the data. Undersampling was also achieved using the ClusterCentroids algorithm. Even a combination of over and undersampling methods were used via the SMOTEEN algorithm. Additionally, BalancedRandomForestClassifier and EasyEnsembleClassifier were introduced and used to allow machine learning to work its magic to predict credit risk. 

# Results

**Naive Random Oversamping**
![](images/naive_random_oversampling.png)

- Using the Naive Random Oversampling algorithm, the image above shows this algorithm producing an accuracy score of about 64%.
- The metrics of high risk precision was extremely low at .01 and the recall at a low .66. Low Risk precision was a perfect 1.0, but the recall was at a low .61.

