# Credit_Risk_Analysis

Credit risk is defined as the potential loss arising from a bank borrower or counterparty failing to meet its obligations in accordance with the agreed terms, this is something that all loans companies need to be aware about since this is the main reason they loose money, you can´t tell by looking at somebody if he is goignt o pay you back the money you gave him so in the era we have ways to workaround this issue. Machine Learning is a topic trending in all plataforms and all subjects, it can be use for medicine, ecology and artificial intelligence and i´ts an everyday growing field, one of the most common use is to predict values with information from before, this is a quick explanation of Supervised Learning and it has the power to see if somebody is going to pay you back.

# Metodology and materials
- Sickit Learn
- Python 3.7
- Imbalance Learn
- Jupyter Notebook

First the data was cleaned and this is a must have skill for any data user, after that the X and y variable where splitted into train (75%) and test (25%), 3 models where created, the first one was a Logistic Regressor with 4 different methodologies to eliminate the noise from the sampling, the algorithms where Naive Random Oversampling,  Smote Oversampling, Cluster Centroids undersampling and SMOTEEN over and under sampling, the other 2 models where Balanced Random Forest and Adaboost

# Results
Overall the precision for the high risk category was low, the highest being 0.07 from the AdaBoost, this means all the models had a high number of false positives, for all the Logistic Regression the recall was really low with less than 70, this made our Logistic Regression model be as good as tossing a coin so they are tossed asside, but if we talk about boosting and bagging both models did preatty well, both cases had almost the same scores with recall of 91 for high risk and 94 for low risk, precision of 0.07 for high risk and 1.00 for low risk, this makes them ideal candidates if any one wants to apply them in their bussines



![OVERSAMPLING](https://user-images.githubusercontent.com/100168991/198496331-f27d277b-763b-4138-8e5b-edf46b138b16.png)

SMOTE OVERSAMPLING

![Smoteen](https://user-images.githubusercontent.com/100168991/198496333-43b98be8-4555-4b04-99b1-4c3d7384d50f.png)

SMOTEEN OVER AND UNDER SAMPLING


![undersamplinh](https://user-images.githubusercontent.com/100168991/198496334-ad05777b-c9da-4a9f-93e0-3cc292f34c57.png)

CLUSTER CENTROIDS UNDERSAMPLING


![adaboost](https://user-images.githubusercontent.com/100168991/198496335-434d730f-c3a8-4959-bfc0-affdc5f21df3.png)

ADABOOST BOOSTER
![balanced forest](https://user-images.githubusercontent.com/100168991/198496337-92fc48f2-d9a1-4e7e-93aa-bb035e63286a.png)

BALANCED RANDOM FOREST


![Naive](https://user-images.githubusercontent.com/100168991/198496338-7d309022-7853-40ff-a140-96c3b1c081b1.png)

NAIVE OVERSAMPLING
