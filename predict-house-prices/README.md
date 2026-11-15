# 1970s Boston House Prices and Prediction

![](https://i.imgur.com/WKQ0nH2.jpg)

## Project Overview

---

The aim of this project is to build a model that can provide a price estimate based on a home's characteristics like:

1. The number of rooms.
2. The distance to employment centres.
3. How rich or poor the area is.
4. How many students there are per teacher in local schools, etc.

---

## Tools and Libraries Used

1. `import pandas as pd`
2. `import numpy as np`
3. `import seaborn as sns`
4. `import plotly.express as px`
5. `import matplotlib.pyplot as plt`
6. `from sklearn.linear_model import LinearRegression`
7. `from sklearn.model_selection import train_test_split`

---

## 1. Data Cleaning

1. `There are 0 NaN values and 0 duplicated values in this dataset`

## 2. Exploratory Data Analysis

1. `There are 18.46 students per teacher on average.`
2. `The average price of a home in the dataset is: 22.53`
3. `The minimum CHAS value is: 0.0, and the maximum CHAS value is: 1.0`
4. `The minimum number of rooms per dwelling is: 3.561, the maximum number of rooms per dwelling is: 8.78`

## 3. Regression

1. `The predicted premium for one extra room is~$3,110.`
2. `The model's fit was succesfully improved. The original model had an R_squared of 0.7501, while the new one has an R_squared of 0.7930. That's 75% vs 79%. The new model explains more variation in house prices than the previous one after regression using log prices.`

## How to run

1. `Open an IDE like cursor, vscode etc.. or an application like anaconda navigator. Essentially anything that lets you open a .IPYNB file.`
2. `Install the requirements.txt.`
3. `You should be able to run each cell after this.`
