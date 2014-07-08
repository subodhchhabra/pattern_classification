# Outline

Title: Machine Learning & Supervised Classification: Python vs. R  

Authors: Sebastian Raschka and Vahid Mirjalili


### 1 General Introduction

### 2 General Description of the data set (no R vs. Python here)

- I would suggest we just use the Iris data set

<hr>
***below here, everything should be done in Python AND R***
<hr>

### 3 Reading in the Data set  

- from CSV file deposited on GitHub repo

### 4 Exemplary plots

- let's each make a scatterplot similar to this one [http://upload.wikimedia.org/wikipedia/commons/e/ea/Anderson%27s_Iris_data_set.png](http://upload.wikimedia.org/wikipedia/commons/e/ea/Anderson%27s_Iris_data_set.png)
	
	
### 5 Dividing into Test and training data sets  
	
- randomly divide into 60% training and 40% test data set	
- after we did it in Python and R, we save either version as CSV so that the exact same test and training datasets are used for the following tasks in Python and R  
	
### 6 Feature Scaling - Standardizing

- standardize data set to &mu;=0 and &sigma;=1


### 7 Linear Transformation via Principal component analysis

- I would say with dimensionality reduction onto a 2D subspace (so we can make nice scatter plots)

- 2D scatter plot after the PCA to compare results

### 8 Classification using SVM


#### 8.1 Training the classifier

- training the classifier on the 2D PCA-transformed training data set

#### 8.2 Plotting decision regions

- plotting the decision regions on the training dataset

#### 8.3 Classification

- classification on the test dataset
- confusion matrix and prediction accuracy

#### 8.4 Discussion of the results


### 9 Conclusion

 