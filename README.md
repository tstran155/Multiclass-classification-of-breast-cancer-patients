# Multiclass classification of breast cancer patients

Breast cancer is the most common cancer and the leading cause of cancer-related deaths in women. Cancer is typically associated with genetic abnormalities. People with the same disease stage and similar clinical characteristics may have different treatment responses and overall survival rates. Therefore, it is important to accurately predict the survival time and prevent unnecessary surgical procedures.

In this notebook, I built gradient boosting classifier and neural network models to classify and predict the survival rates of breast cancer patients. The dataset used in this work included 1,980 primary breast cancer samples and can be found on Kaggle website.

https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric

There are two notebooks -gradient boosing classifier and neural network- in this repository. Their file structure is similar except for Section #4 and 5.

1. Prepare Problem

a) Load libraries

b) Load dataset

2. Summarize Data

a) Descriptive statistics

b) Data visualizations

3. Prepare Data

a) Data Cleaning

b) Feature Selection

c) Split Dataset into Train and Test Sets 

d) Data Transforms

4. Evaluate Algorithms

a) Spot check algorithms 
   
- Notebook 1: Standard algorithms (KNeighborsClassifier, DecisionTreeClassifier, GaussianNB, SVC)
                 
              Ensemble algorithms (AdaBoostClassifier, GradientBoostingClassifier, RandomForestClassifier,ExtraTreesClassifier) 
   
- Notebook 2: Ensemble algorithm (XGBoost)
                 
              Neural network algorithm (Keras Sequential)
                 
b) Compare algorithms

5. Improve Accuracy by Tuning Model's Parameters

6. Finalize Model

a) Predictions on validation dataset (best algorithm)

b) Save model for later use

7. Conclusions
