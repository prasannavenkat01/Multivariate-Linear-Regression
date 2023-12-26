# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1: import pandas as pd

### Step2: read the csv file

### Step3: get the values of x and y variables

### Step4: create the linear regression model and fit

### Step5: predict the co2 emiision of a car where the weight is 2300kg,and the volume is 1300cm and cube.

### Step6: print the predicted output.
## Program:
```

Developed by : PRASANNA V
Register number : 23006873
import pandas as pd
from sklearn import linear_moedel
df = pd.read_csv("carsemission.csv")
x = df[['weight','volume']]
y = df['CO2']
regr = linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictedCO2 = regr.predict([[3300,1300]])
print('predicted CO2 for the corresponding weight and volume',predictedCO2)




```
## Output:

### Insert your output
![Screenshot 2023-12-26 175312](https://github.com/prasannavenkat01/Multivariate-Linear-Regression/assets/150702500/8c4d1900-b237-4315-9e17-a026e5fe8c12)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
