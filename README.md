# Credit_Risk_Analysis

## Overview of Project

For this project, we were tasked to predict credit risk for Fast Lending, a peer-to-peer lending services company. We will use Python and the Scikit-learn library to build and evaluate several machine learning models to predict credit risk by adopting the following procedures on credit card dataset:

+ **Data Oversampling:** we’ll oversample the data using the RandomOverSampler and SMOTE algorithms
+ **Data Undersampling:**  we’ll undersample the data using the ClusterCentroids algorithm
+ **Combinbation of over- and under- sampling:** we’ll use a combinatorial approach of over-and undersampling using the SMOTEENN algorithm.
+ **Comparing machine learning models that reduce bias:**  we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.



## Results

## Random Over Sampler (Naïve Radom Oversampling Model)

![random_oversampler](https://github.com/nnamdiilokah/Credit_Risk_Analysis/blob/main/Figures/random_oversampler.png)

+ The balanced accuracy score is 65.7%
+ The precision for high risk is 1%
+ The recall for high risk is 71%
+ The precision for low risk is 100%
+ The recall for low risk is 60%


## SMOTE Oversampling Model

![smote_oversampler](https://github.com/nnamdiilokah/Credit_Risk_Analysis/blob/main/Figures/smote_oversampler.png)

+ The balanced accuracy score is 66.2%
+ The precision for high risk is 1%
+ The recall for high risk is 63%
+ The precision for low risk is 100%
+ The recall for low risk is 69%


## Undersampling: Cluster Centroids Model

![cluster_centroids](https://github.com/nnamdiilokah/Credit_Risk_Analysis/blob/main/Figures/cluster_centroids.png)

+ The balanced accuracy score is 54.4%
+ The precision for high risk is 1%
+ The recall for high risk is 69%
+ The precision for low risk is 100%
+ The recall for low risk is 40%


## Combination Sampling: SMOTEENN Model

![smotteen](https://github.com/nnamdiilokah/Credit_Risk_Analysis/blob/main/Figures/smotteen.png)

+ The balanced accuracy score is 64.4%
+ The precision for high risk is 1%
+ The recall for high risk is 72%
+ The precision for low risk is 100%
+ The recall for low risk is 57%



## Summary



