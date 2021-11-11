# Banking-Prediction
Banking  predictin of customers if they will convert or not. 


This dataset is from <a href='https://www.kaggle.com/prakharrathi25/banking-dataset-marketing-targets'>Kaggle</a>



The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).


**Content**

The data is related to the direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed by the customer or not. The data  contains one dataset:
- train.csv: 45,211 rows and 18 columns ordered by date (from May 2008 to November 2010)

**Detailed Column Descriptions**

bank client data:

1.  age (numeric)

2.  job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
"blue-collar","self-employed","retired","technician","services")

3.  marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)

4.  education (categorical: "unknown","secondary","primary","tertiary")

5.  default: has credit in default? (binary: "yes","no")

6.  balance: average yearly balance, in euros (numeric)

7.  housing: has housing loan? (binary: "yes","no")

8.  loan: has personal loan? (binary: "yes","no")

9.  contact: contact communication type (categorical: "unknown","telephone","cellular")

10.  day: last contact day of the month (numeric)

11.  month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")

12.  duration: last contact duration, in seconds (numeric)

13.  campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

14.  pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)

15.  previous: number of contacts performed before this campaign and for this client (numeric)

16.  poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Output variable (desired target):

17.  y - has the client subscribed a term deposit? (binary: "yes","no")

Missing Attribute Values: None



**Citation**

This dataset is publicly available for research. It has been picked up from the <a href='https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#'>UCI Machine Learning</a> with random sampling and a few additional columns.

Please add this citation if you use this dataset for any further analysis.

S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
