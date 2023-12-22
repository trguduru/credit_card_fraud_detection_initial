### Credit Card Fraud Detection

**Author**
Guduru, Thirupathi Reddy (https://github.com/trguduru)

#### Executive summary

#### Rationale
The rationale for detecting fraud in a credit card transaction is to eliminate the dollar waste for a financial institution. And also build trust with its customers.
#### Research Question
Whether a given credit card transaction is a fraudulent transaction or not.

#### Data Sources
The dataset for this use case is here - https://www.kaggle.com/datasets/kartik2112/fraud-detection .
This is simulated data using this simulation tool -  https://github.com/namebrandon/Sparkov_Data_Generation


This is a simulated credit card transaction dataset containing legitimate and fraudulent transactions from the duration of 1st Jan 2019 to 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.

#### Methodology
I have used the following tools and techniques to classify whether a transaction is fraud or not in machine learning.
##### Data Analysis
This dataset has more than 1M rows and more than 20 features.To understand how each feature's data is and how they are related to each other have done the following analysis using various plots from *matplotlib* , *seaborn* and *plotly*.

![Transaction Amount > 5000](images/card_amt_5000.png) ![Transaction Amount > 1000 and < 5000](images/card_amt_1000.png)

##### Data Processing
* Cleaned some of the unnecessary columns like transaction number, merchant name, customer names etc, as these dont add any values in model evaluation.
* 
##### Feature Engineering

##### Model Evaluation
Evaluated the following models
* LogisticRegression
* KNN
* DecisionTreeClassifier
* SVM
* GaussianNB
* SGDClassifier


#### Results
What did your research find?

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Initial Analysis](initial_EDA.ipynb)


##### Contact and Further Information
