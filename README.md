# Iris Flower Data Analysis
In this project, we will be analysing iris flower data set to classify different species into their respective classes. The iris flower dataset consists of 150 entries from 3 different species, 50 samples from each specie. The species are setosa, versicolor and virginica. There are four numerical feature columns and one column which contains categorical variable or targets.

## How to get the dataset?
Either download from kaggle website or UCI Machine Learning repository onto your local machine or import dataset provided by sklearn. 

## Project Directory 
The project directory consists of following jupyter notebook files:
* EDA_and_Statistical_Testing 
* Machine_Learning_Classifiers

1. EDA_and_Statistical_Testing
* In EDA and Statistical Testing, we will be first exploring the dataset with the help of visualization tools such as Matplotlib and seaborn library. Before EDA, we need to make   sure that our data must be clean and it should not have outliers and anomalies. After getting familiar with the data, an exploratory data analysis was done by making pairplots and density plot for different features and species. 
* Statistical testing includes Univariate and Bivariate testing. In Univariate testing, a 'box plot' was made to measure the variability of the data. Then we measured degree of asymetery or skewness and kurtosis from different features. This gave us some insights about the data such as we found out that features "petal length" and "petal width" are not normally distributed and they have strong skewness and significant excess kurtosis.
* Bivariate testing includes measure of correlation between the features with the help of "pearson r correlation coefficient". This was depicted with the help of a nice heat map plot. 

2. Machine_Learning_Classifiers
* First the dataset is splitted into train and test parts. 25% of the data is used for testing the model while 75% is used to train the model. 
* Differnt classical machine learning approaches such as Logistic regression, Naive Bayes Classifier, K nearest neighbors, support vector machines, and ensemble techniques such as random forest is applied on the train set to train the model. A grid search algorithm is also used to find best hyperparameters for classifiers. 
* Some important metrics including classification_report from sklearn.metrics and confusion_matrix is used to check the performance of the model. 
* There are some pros and cons of each classifiers. In a nutshell, classifiers including logistic regression and Random forest works best for this use case.  

*Note: 
<br>
In the upcoming tasks, a new metric "roc_auc_curve" is used to compare the performace of different classifiers with the help of a graph. 
