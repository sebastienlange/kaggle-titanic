### Kaggle-titanic
[Titanic Machine Learning From Disaster](https://www.kaggle.com/c/titanic) is my first data science project and also my first submission in a Kaggle competition. 
The goal was to have a first real experience in machine learning, python, sklearn and try many different classifiers.

### Installation:

The code was tested with Python 3.6.

The packages I used to run the code are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``kaggle-titanic`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n kaggle-titanic python=3.6 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](https://conda.io/en/latest/) section of the conda documentation.

### Kaggle Competition | Titanic Machine Learning from Disaster

>The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew.  This sensational tragedy shocked the international community and led to better safety regulations for ships.

>One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.  Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

>In this contest, we ask you to complete the analysis of what sorts of people were likely to survive.  In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

>This Kaggle Getting Started Competition provides an ideal starting place for people who may not have a lot of experience in data science and machine learning."

From the competition [homepage](https://www.kaggle.com/c/titanic).

### Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

#### This Notebook will show basic examples of:
#### Data Handling
- Importing and Cleaning Data with [Pandas](https://pandas.pydata.org/)
- Exploring Data through Visualizations with [Seaborn](https://seaborn.pydata.org/)

#### Data Analysis - Supervised Machine learning Techniques:
- Feature ranking with recursive feature elimination and cross-validated selection of the best number of features with [RFECV](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html)
- Benchmarks multiple classifiers among [XGBClassifier](https://xgboost.readthedocs.io/en/latest/python/python_api.html), [AdaBoostClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html), [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html), [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- Benchmarks multiple hyper parameters with [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) and cross validation
- Displaying results
- Refining hyper parameters for the best model with [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)

#### Valuation of the Analysis
- K-folds cross validation to valuate results locally
- Output the results from the Notebook to Kaggle

Competition Website: https://www.kaggle.com/c/titanic
