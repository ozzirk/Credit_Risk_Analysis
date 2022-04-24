# Credit_Risk_Analysis

## Machine learning to analyze credit risk

**Overview of the analysis**

In this analysis, we are trying to predict the difficult problem of credit card risk. Datasets have shown that good candidates far outnumber bad ones, so we will need to build multiple models using different resampling techniques to try to predict outcomes accurately. 
    
**Results**  
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

 1. **Naive Random Oversampling:** Using the oversampling method, we were able to achieve 66% accuracy with an average precision of 99%
 ![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/Oversampling.jpg?raw=true)
 
 2. **SMOTE:** Using the smote method, we were able to achieve  65% accuracy with an average precision of 99%
 ![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/SMOTE.jpg?raw=true)
 
 3. **Undersampling:** Using the undersampling method, we were able to achieve 54% accuracy with an average precision of 99%
 ![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/UNDER.jpg?raw=true)
 
 4. **SMOTEEN:** Using the SMOTEEN method, we were able to achieve 64% accuracy with an average precision of 99%
![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/SMOTEEN.jpg?raw=true)

 5. **Balanced Random Forest:** Using the balanced random method, we were able to achieve a 79% accuracy with an average precision of 99%
 ![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/BalancedRandom.jpg?raw=true)
 
 6. **Easy Ensemble:** Using the easy ensemble method, we were able to achieve a 93% accuracy with an average precision of 99%
![enter image description here](https://github.com/ozzirk/Credit_Risk_Analysis/blob/main/EasyEnsemble.jpg?raw=true)


**Summary**  
In summary, one of the main things that stuck out was the consistent level of precision across all of the methodologies we tested. This could be evidence of an underlying issue within the data that may need to be investigated further. Overall, I would feel comfortable moving forward with using the easy ensemble method as it rated the highest in terms of accuracy and precision. 
