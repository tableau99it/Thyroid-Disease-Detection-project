#  Titles :- Thyroid Disease-Detection
# Introduction:- 
Machine learning is implemented in many fields today. But most significant improvements are made in the field of 
medicine. To detect thyroid disease, blood tests and medical imaging are performed (ultrasound). Awareness about thyroid 
disease is necessary as it will play a significant role in the early detection and curing of this problem. The thyroid is an organ 
in the human body. It produces the hormone required by the human body. The hormones travel in the bloodstream, and it 
affects the metabolism and growth of humans. It is located below Adam’s apple. Thyroid functionality is used for the 
interpretation and diagnosis of the disease. The thyroid gland is one of our body's most vital organs.
The thyroid gland produces hormones that control the growth and metabolism 
used for the body’s energy purposes. The thyroid gland also contributes to development in children and adults. The thyroid 
gland also maintains body temperature. 

One of the most definitive ways to diagnose a thyroid problem is through blood tests. 
Thyroid blood tests are used to tell if your thyroid gland is functioning properly by measuring the amount of 
thyroid hormones in your blood. These tests are done by taking blood from a vein in your arm. Thyroid blood tests are 
used to see If your body makes too much thyroid hormone, you can develop a condition called Hyperthyroidism. If your 
body makes too little thyroid hormone, it’s called Hypothyroidism. Both conditions are serious and need to be treated 
by your healthcare provider. 

The thyroid gland produces two main hormones—triiodothyronine (T3) and thyroxine (T4). Thyroid disease is a common cause of
medical diagnosis and prediction, with an onset that is difficult to forecast in medical research.That's why i have tried to best ML algorithm which is 
given 99% accuracy predicted disease diagnosis.

# Technologies:-
I used the python language and Machine learning as well as worked on jupyter notebook.

Python's version - 3.10.6 
and within this have to used python libraries and as well as versions like a.... 

pandas      1.4.3

numpy       1.23.1

matplotlib  3.5.3

seaborn     0.11.2

Firstly you have to necessary to import all above libraries. it will help when your lunching the project.

Apart from this i tried to various Machine learning algorithms......

DecisionTreeClassifier

KNeighborsClassifier

naive_bayes (GaussianNB)

support vector machine

LogisticRegression

RandomForestClassifier

LinearRegression

# Launch
![image](https://user-images.githubusercontent.com/106155354/184474198-7173276d-58f2-486d-81b7-10189e2cbbeb.png)

import pandas as pd 

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

df = pd.read_csv("d:/data/hypothyroid.csv")
df.head()

x = df.drop('Label',axis=1)
y = df['Label']

from sklearn.model_selection import train_test_split











