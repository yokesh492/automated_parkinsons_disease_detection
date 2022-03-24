# Challenge 2

## Problem statement:
                    
Pick up the latest machine learning use case in the medical domain from aresearch paper and implement it by yourself. 
You can take help from the GitHub repositories of those researchers.

## What I did?:

I got the reasearch paper from Researchgate.net, in the topic of detection of parkinson's disease : [Detection_of_Parkinson](https://www.researchgate.net/publication/355393889_Detection_of_Parkinson%27s_Disease_by_Employing_Boosting_Algorithms)
But unfortunately,I couldn't get the github code for this paper, I tried my best to implement the paper.

### Data:
  The dataset that has been deployed for this investigativestudy is taken from the UCI machine learning repository[28]. The Parkinson’s disease (PD) classification dataset isconstituted at the Department of Neurology in CerrahpaÅŸaFaculty of Medicine, Istanbul University .
  
### Models:
As per the refrence paper,
1. **Feature selection** : The dimension of the data is reduced by the first 756 to 257 then with the help of the **K_Best** algorithm we again reduced to 20 columns
2. **Testing with boosting algorithm**: Adaboost,gradientboosting,XGB,LGBM with these boosting algorithm we select the best model with help of hyperparameter tuning with gridsearch cv.
3. **FinalModel** : Atlast we select the best model by comparing with classification report of all the model

## Conclusion:
LGBM algorithm give the best accuracy with good f1 score , so the final model is LGBM . eventhough it is good algorithm with 89% accuracy ,while comparing with train evaluation ,I got to know the that it overfitted .
## Inference 
we need to do again hyperparameter tuning to controle the overfitting and try to do better in feature selection . 

# THANK YOU 
