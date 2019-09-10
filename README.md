[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AashitaK/ML-Workshops/master)

This repository is forked and adapted (currently not very adapted) from a four part workshop developed by AashitaK at Harvey Mudd College.

### Introduction:

The workshop series is designed with a focus on the practical aspects of machine learning. We will be working in Python and using real-world datasets from [Kaggle](https://www.kaggle.com), the machine learning platform most suited for the “learn-by-doing” philosophy. The series is targeted towards complete beginners familiar with Python, but it is also designed adaptively so that you will be challenged even if you have some familiarity with machine learning tools.

### Topics covered in the guided sessions and hands-on exercises:  
Session 1: Exploratory Data Analysis and Feature Engineering using Pandas - 1
- Pandas dataframes as the data structure for datasets
- Converting csv files to dataframes
- Slicing and indexing dataframes using conditionals as well as iloc and loc methods.
- Statistical summary and exploration of dataframes
- Detecting and filling missing values in the dataframes
- Regular expressions for data extraction
- Feature engineering such as creating new features
- Basic statistical plots using `matplotlib` and `seaborn`
- Correlation among features
- Basic operations such as dropping rows/columns, setting index, replacing values of a column using a dictionary, etc.

Session 2: Exploratory Data Analysis and Feature Engineering using Pandas - 2
- Split-apply-combine operations by grouping rows of a dataframe
- Encoding categorical variables
- Concatentating and merging dataframes
- More operations such as sorting the rows, creating a dataframe from the scratch, etc.

Session 3: Model Building, Tuning and Validation using Scikit-learn - 1
- Overfitting and underfitting of models
- Regression algorithms
    - Linear Regression
    - Polynomial Regression
    - Rigde Regression
    - Lasso Regression
- Model Validation
- Tuning regularization paramter
- Evaluation metrics for regression - R-squared and Root Mean-Squared Error (RMSE)
- Normalization and scaling of features

Session 4: Model Building, Tuning and Validation using Scikit-learn - 2
- Classification algorithms
    - Logistic Regression
    - Decision Trees
    - k-Nearest Neighbors
    - Support Vector Machines
    - Random Forests
- Evaluation metrics for classification
    - Classification accuracy
    - Confusion matrix
    - Decision Threshold
    - Precision and Recall
    - F1 score
    - Area Under ROC curve
- Dimensionality reduction (Optional)
    - Principal Component Analysis (PCA)
- k-fold Cross-validation
- Maximum Voting Classifiers

### Pre-requisites:
* Python programming basics (HMC CS-5 or equivalent should suffice)
* Some familiarity with common statistical concepts (HMC MATH-35 or equivalent should suffice)

### Learning materials:
The learning material is shared in the [Github repository](https://github.com/AashitaK/ML-Workshops). You can download the entire repository and run the notebooks in your system by installing Jupyter notebooks using [Anaconda distribution with python 3 version](https://www.anaconda.com/distribution/). Another option would be to fork the notebooks from the following links and run it using Kaggle Kernels - a cloud computing environment that does not require any installation.  
* Session 1
    * [Introductory notebook](https://www.kaggle.com/aashita/introduction-to-ml-workshop-series)
    * [Guided Session 1](https://www.kaggle.com/aashita/guided-session-1)
    * [Exercise 1](https://www.kaggle.com/aashita/exercise-1)
* Session 2
    * [Guided Session 2](https://www.kaggle.com/aashita/guided-session-2)
    * [Exercise 2](https://www.kaggle.com/aashita/exercise-2)
* Session 3
    * [Guided Session 3](https://www.kaggle.com/aashita/guided-session-3)
    * [Regression algorithms](https://www.kaggle.com/aashita/regression-algorithms)
    * [Exercise 3](https://www.kaggle.com/aashita/exercise-3) (Bike Share Demand competition)
* Session 4
    * [Classification algorithms](https://www.kaggle.com/aashita/classification-algorithms)
    * [Miscellaneous concepts in Machine Learning](https://www.kaggle.com/aashita/guided-session-4)
    * [Exercise 4](https://www.kaggle.com/aashita/exercise-4) (Titanic competition)

The solutions for the guided sessions and exercise notebooks are available in the [Github repository](https://github.com/AashitaK/ML-Workshops) but not on Kaggle. The material is designed to be self-sufficient and useful in case you miss a session.

### Team (original):
Instructor: Aashita Kesarwani  
TAs: Rex Asabor, Ben Langton and Qualan Woodard
