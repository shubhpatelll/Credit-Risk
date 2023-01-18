# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
Use supervised machine learning to determine which credit card application is considered high risk or low risk.  The challenge requires to use the credit card credit dataset from Lending Club, a peer-to-peer lending services company. Use following models to determine which will be the most effective model: 4 Resampling Models (Random Oversampling,SMOTE Oversampling, Undersampling and SMOTEENN) and 2 Ensemble Classifiers (Balanced Random Forest Classifier,Ensemble AdaBoost Classifier). 

## Results: 

### Random Oversampling 

 * balanced accuracy: 64%
 * precision (high_risk): 1%
 * precision (low_risk): 100%
 * Recall (high_risk): 60%
 * Recall (low_risk): 68%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/Naive_Random_Oversampling.png" /><br>
</p>



### SMOTE Oversampling

 * balanced accuracy: 63.7%
 * precision (high_risk): 1%
 * precision (low_risk): 100%
 * Recall (high_risk): 60%
 * Recall (low_risk): 68%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png" /><br>
</p>

### Undersampling

 * balanced accuracy: 59.5%
 * precision (high_risk): 1%
 * precision (low_risk): 100%
 * Recall (high_risk): 62%
 * Recall (low_risk): 57%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/Undersampling.png" /><br>
</p>

### SMOTEENN

 * balanced accuracy: 63%
 * precision (high_risk): 1%
 * precision (low_risk): 100%
 * Recall (high_risk): 71%
 * Recall (low_risk): 55%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png" /><br>
</p>

### Balanced Random Forest Classifier 

 * balanced accuracy: 78.7%
 * precision (high_risk): 4%
 * precision (low_risk): 100% 
 * Recall (high_risk): 67%
 * Recall (low_risk): 91%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_Classifier.png" /><br>
</p>

### Ensemble AdaBoost Classifier

 * balanced accuracy: 92%
 * precision (high_risk): 7% 
 * precision (low_risk): 100% 
 * Recall (high_risk): 91% 
 * Recall (low_risk): 94%

<p align="center">
<img src = "https://github.com/dhaval-28/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_AdaBoost_Classifier.png" /><br>
</p>

## Summary: 
Above results show summary of each model and how each model performed. 
Ensemble AdaBoost Classifier model seems to performed the best.  The accuracy rate of this model is the highest among all 6 models. Precision and Recall scores are also higher among all models. 
