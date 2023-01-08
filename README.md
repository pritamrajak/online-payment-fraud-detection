# online-payment-fraud-detection
<br><br>
To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud. For this task, I collected a dataset (https://www.kaggle.com/ealaxi/paysim1/download ) from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:
<br><br>
step: represents a unit of time where 1 step equals 1 hour<br>
type: type of online transaction<br>
amount: the amount of the transaction<br>
nameOrig: customer starting the transaction<br>
oldbalanceOrg: balance before the transaction<br>
newbalanceOrig: balance after the transaction<br>
nameDest: recipient of the transaction<br>
oldbalanceDest: initial balance of recipient before the transaction<br>
newbalanceDest: the new balance of recipient after the transaction<br>
isFraud: fraud transaction<br>
I hope you now know about the data I am using for the online payment fraud detection task. Now in the section below, I’ll explain how we can use machine learning to detect online payment fraud using Python.<br>

