### The proble statement given by Analytics Vidya in Summer Training Hackathon


![image](https://user-images.githubusercontent.com/56762253/182018810-f98ad76d-4bef-44fa-a98c-0307a201210b.png)


![image](https://user-images.githubusercontent.com/56762253/182018704-cded1c7f-f348-47a9-8319-6bf83e203e12.png)

# Loan-Default-Prediction
Can you predict if an applicant will default the loan or not in the future?

### Problem Statement

MyHom is a finance company that lends housing loans at the best and most affordable interest rates to customers. In recent times, the company incurred heavy losses due to loan defaults. Most applicants failed to repay the loan as per the promissory note.


In order to avoid such losses, the company has decided to build a system for identifying the loan defaulters automatically based on data. This will help the company to identify the potential applicants and ensure the smooth running of the entire process.


Now, the company challenges the Data Science community to build a smart AI system to predict the probability of an applicant defaulting the loan or not in the future.



### About the Dataset


You are provided with the past applicant’s data containing the demographic information, loan attributes, and target variable indicating if an applicant will default the loan or not.



### Data Dictionary


You are provided with 3 files - train.csv, test.csv, and sample_submission.csv



### Train and Test Data


The train and test set contains the different attributes related to demographic and loan information of the applicants such as age, profession, no. of active loans, loan default in previous loans, and so on. The training set contains the target variable loan_default and you need to predict the target variable in the test set.




![image](https://user-images.githubusercontent.com/56762253/182018500-6a800ce0-6e79-4cba-96ea-08bff6807ae7.png)





### Submission File Format


### sample_submission.csv contains 2 variables - 




![image](https://user-images.githubusercontent.com/56762253/182018539-95d8f73b-7d04-47a7-8e4c-db87c5f68edd.png)





#### Evaluation metric


The evaluation metric for this hackathon would be the macro F1 Score.


## Approach

1. Understand the dataset
2. Fill in missing values
3. Use label encoder for categorical features
4. Feature Engineering
5. Model Selection by trying various models with cross validation
6. Feature importance
7. Final Model training
