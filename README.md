# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import panda module as pd

### Step2
<br>mport linear model from sklearn

### Step3
<br>Read the file cars.csv

### Step4
<br>Assign the values for x and y as required

### Step5
<br>Create the linearRegression model and predict the output

## Program:
```
Developed by: rohith r
Register number: 212222230121

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))






```
## Output:
![244585266-a954498e-cce7-4fcd-9dbf-b39cc7f595f2](https://github.com/Rohithravi333/Multivariate-Linear-Regression/assets/119394126/aa50bd8a-14db-4f73-865b-18423279340d)
## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
