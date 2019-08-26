# A study on Amazon Review Classification using Ensemble Methods.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
Kyphosis is an abnormally excessive convex curvature of the spine. 
The kyphosis data frame has 81 rows and 4 columns, representing data on children who have had corrective spinal surgery. 
We are required to build a model to predict if a kyphosis (a type of deformation) was present after an operation.

`Predictors:`
```
Age: in months
Number: the number of vertebrae involved
Start: the number of the first (topmost) vertebra operated on
```

`Target:`
```
Kyphosis (0: Absent, 1: Present)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_Ensemble_Kyphosis_Desease_Classification/blob/master/kyphosis.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Ensemble_Kyphosis_Desease_Classification/blob/master/RF%20-%20Kyphosis%20Disease%20Classification.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Visualizing the Variables
      3.2 Data Cleaning
    4 Train Test Split
    5 Select and Train a Model
      5.1 Decision Tree Model
    6 Apply Model on Test Set
    7 Improve the Model
      7.1 Random Forest Model
    ```   
    
### Model Performance
The model has an average `Precision` of 87% and `Recall` of 84%.
![alt text](https://github.com/zhenyu92/ML_Ensemble_Kyphosis_Desease_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
