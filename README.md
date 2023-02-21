## About The Project
<br>
<p align='center'>
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fmachinelearninggeek.com%2Fanalyzing-sentiment-of-restaurant-reviews%2F&psig=AOvVaw1-nl_symjnPvjmpIaTUJpC&ust=1677047565699000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCNClxav_pf0CFQAAAAAdAAAAABAJ" width='70%' >
</p>
<br>

BreastCancerDetection is a machine learning project hosted on GitHub that aims to detect breast cancer using machine learning algorithms. The project is written in Python and uses the Scikit-learn library for implementing machine learning algorithms.

The project includes a dataset of breast cancer patients with several features including tumor size, tumor shape, and other characteristics. The goal is to use machine learning algorithms to classify whether a breast tumor is malignant or benign based on these features.


- Data Preprocessing.
- Dealing With MissingValues
- Length of Messages
-  Cleaning the text
- Create the Bag of words Model.
- Splitting the dataset.
- Part 2 : Model Building
- Naive Bayes.
- XGBoost Classifier.
- Part 3:Final Model(XGBooster Classifier).

<br>

### Built With

![Python](https://img.shields.io/badge/Python%20-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)



<br>

## Importing the libraries and Dataset

This is a sample for Restauraunt_Reviews Classification.
for classifying restaurant reviews into positive and negative categories. The goal is to train a machine learning model that can accurately predict whether a given restaurant review is positive or negative.
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

Data

```
The data for this project consists of a set of restaurant reviews, each of which is labeled as either positive or negative. The data is stored in two separate CSV files, one for positive reviews and one for negative reviews. The CSV files contain the following columns:

Review: The text of the restaurant review.
Label: Either "Positive" or "Negative", indicating whether the review is positive or negative.

```

Preprocessing:

```
Before training the machine learning model, the data is preprocessed by performing the following steps:

Tokenization: The text of each review is split into individual words, or tokens.
Lowercasing: All tokens are converted to lowercase to standardize the data.
Stop word removal: Common stop words (e.g. "the", "and", "a") are removed from the data to reduce noise.
Stemming: Tokens are stemmed using the Porter stemming algorithm to reduce inflectional forms to their base form.
```

Modeling

```
The machine learning model used for this project is a Naive Bayes model and XGBoost Classifier. The model is trained on the preprocessed data using scikit-learn. The model is evaluated using accuracy_score, confusion_matrix is used as the evaluation metric.
```

<br>

</div>
