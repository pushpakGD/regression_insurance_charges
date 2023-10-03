# Regression, medical insurance charges

The project is written in Python in a Jupyter Notebook format
The project utilizes multiple ML models to predict the medical insurance charges found at following link: DataSet Link from kaggle.com

### EDA Conclusions Written Information: 
- There is a total of 7 features which are:
- age, this parameter represents the age of an individual in years
- sex, this parameter represents the sex of an individual either Male or Female
- bmi, this parameter represents the bmi of an individual as a numerical value
- children, this parameter represents the number of children an individual has as a numerical value
- smoker, this parameter represents the smoking status of an individual
- region, this parameter represents the region an individual lives in
- charges, this is the label parameter and it represents each individual's medical costs billed by the health insurance

 A count plot of the "Label" column, which is Charges
 The plot displays that majority of people have medical charges below $20000
![mllnsu1](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu1.png)

 A correlation plot between the Charges column & all the other numerical columns
 The highest correlation between the numerical columns and the Charges column happens to be 29.9% for the age column, then, 19.8% for the bmi column, and 6.7% for the childern column
![mlInsu2](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu2.png)

 A correlation heatmap between all the numerical features
 The age column seems to have the highest correlation with the charges column and the bmi column
 
![mlInsu3](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu3.png)

A count plot that analyzes the relationship between the sex and childern columns
Both males and females have a balanced number of children
The most number of childern is 0 and the lowest number of childern is 5
![mlInsu4](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu4.png)

A count plot that analyzes the relationship between the sex and smoker columns
Both males and females have a balanced degree of smoking
The data contains less smoking individuals

![mlInsu5](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu5.png)

A count plot that analyzes the relationship between the sex and region columns
all areas have a close number of males and females. However, more males and females are from the Southeast region
![mlInsu6](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu6.png)

- A pairplot presenting multiple relationships, while the smoker column is set as a hue
- Changes seem not to increase with increasing the age. However, it increases with smking individuals
- The distrubtion of age seem to be similar throughout all the ages
Non-smokers seem to have more childern
![mlInsu7](https://github.com/pushpakGD/regression_insurance_charges/blob/main/images/mlInsu7.png)
