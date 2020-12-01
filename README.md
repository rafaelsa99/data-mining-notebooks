# Data Exploration Notebooks
Notebooks of the Data Mining course of the Masters in Informatics Engineering of the University of Aveiro.

The Jupyter notebook is an interactive environment for writing and running code.

## Preprocessing
### Exploratory Data Analysis

Exploratory Data Analysis (EDA) is used to study the data and generate hypotheses for further analysis. On the other hand, you can also use it to prepare the data for machine learning algorithms. Steps in data exploration and preprocessing are:
- Identification of variables and data types.
- Statistical Univariate Analysis. Using descriptive parameters and graphical tools (histograms, boxplots)
- Missing value treatment.
- Variable transformations. Transformation to numeric values, scaling, normalization.
- Bivariate Analysis. Statistical parameters (Pearson correlation, ANOVA tests) and graphical tools (heatmaps or scatter plots).

Tasks that can be considered in a data mining project are feature selection and dimension reduction. Both have the goal of decreasing the number of inputs to the predictive (classification) models.

## Classifiers
### Linear Discriminant Functios and KNN

Using scikit-learn facilities the construction of a classifier involves the following the steps:
- Create the classifier, i.e., initialize the object classifier. The hyper-parameter of the classifier are assigned at this phase. Note that there are default values.
- Learning. The object classifier and the training data set (features and labels) are passed to a function named fit.
- The trained classifier can be used to predict. Function predict can be applied to data. This step is used to evaluate the classifier. Therefore, data which was not used in training phase should be considered. Note that there are systematic approaches to achieve this goal.

Linear Classifiers are described by discriminant functions:
```
g(x) = wTx + b
```

The parameters are (w; b). There are diferent algorithms that learn the parameters given the data. For each the hyper-parameters are diferent.

K- Nearest Neighbor is an instance based classifier. Hyper-parameters are the similarity metric and K (number of neighbors).
