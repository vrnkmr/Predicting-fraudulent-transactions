# Predicting-fraudulent-transactions
## Goal
The goal of this research is to train a classifier to classify transactions into fraudulent transactions (where fraudsters steal money from cards) and normal transactions (where normal people are involved) based on a set of characteristics of the transactions.

This task will be solved by means of binary classification using Scikit-Learn and by implementing the following algorithms

- K-Nearest Neighbors method;
- Support Vector Machines method;
- Logistic Regression.

## Results
- A classifier was trained to classify transactions into fraudulent transactions (where fraudsters steal money from cards) and normal transactions (where transactions occur between normal people) based on a set of transaction characteristics. These characteristics included: the type of transaction, the amount of the transaction, the amount of money on the accounts of the two people involved in the transaction before and after the transaction.
- This task was solved by binary classification using Scikit-Learn and by implementing the following algorithms: K-Nearest Neighbors and Logistic Regression. And it turned out that the best classification occurs when the classifier is trained using the nearest neighbors method.
- Also, during the classification, it was found that both the first and second models perfectly classify transactions that are safe, but when classifying fraudulent transactions, confusion arises and the model does not work very well.
- In any case, each classification model has its drawbacks and there are no perfect models. Therefore, this model can be used for further classification of fraudulent transactions. Perhaps it will work better if more fraudulent transactions can be provided for training.
![image](https://github.com/user-attachments/assets/c9f4d19f-49d6-4d30-a8fc-0b608e0faab4)
![image](https://github.com/user-attachments/assets/206fc753-3a8a-4fe6-b77e-d27e4ab6aae9)
![image](https://github.com/user-attachments/assets/cc983ab9-d3ea-4696-a269-099714ebb522)
![image](https://github.com/user-attachments/assets/6387a497-899a-444c-a665-00bfdadf7704)

## Source of data
https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction?resource=download
