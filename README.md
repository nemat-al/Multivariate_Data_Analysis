## Multivariate Data Analysis
Implementing Tasks in Python Programming Language.
The tasks are assignments for Academical Course : "Methods and Models for Multivariate Data Analysis" in ITMO university.

## Index
1. [The analyzed Dataset](#the-analyzed-dataset)
2. [The tasks performed in the file: lab_01](#the-tasks-performed-in-the-file-lab_01)
3. [The tasks performed in the file: lab_02](#the-tasks-performed-in-the-file-lab_02)
4. [The tasks performed in the file: lab_03](#the-tasks-performed-in-the-file-lab_03)
5. [The tasks performed in the file: lab_04](#the-tasks-performed-in-the-file-lab_04)

---
### The analyzed Dataset
#### “House Appliances Energy Dataset”
It is an experimental data used to create regression models of appliances energy use in a low energy
building.
The dataset contains 29 different features; all features are continuous except one. There are 19735
record in the dataset with no missing values. The information in the data are:
- Temperature and humidity inside different rooms in the house. (18 columns)
- Temperature, humidity, pressure, wind speed, visibility and temperature of dew point outside the house. (6 columns)
- Appliances: the energy used in the house. (1 column)
- Lights: energy use of light fixtures in the house. Which is the discreet column. (1 column)
- 2 random variables. (2 columns)
- Date and time of measuring the variables. (1 column).

- The variables are in celsius, in watt, or in percentage. The data is measured each ten minutes for about 4.5 months.
The dataset can be found, [here](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction).

----------

### The tasks performed in the file: [lab_01](https://github.com/Nemat-Allah-Aloush/Multivariate_Data_Analysis/blob/master/1.Analysis%20of%20univariate%20random%20variables/lab_01.ipynb)
#### 'Analysis of univariate random variables'
1. Plotting a non-parametric estimation of PDF.
2. Order statistics estimation and its representation as “box with whiskers” plot.
3. Selection of theoretical distributions that best reflect empirical data.
4. Estimation of random variable distribution parameters using maximum likelihood technique and LS methods.
5. Validation of empirical and theoretical distributions using quantile biplots.
6. Statistical tests.

----------

### The tasks performed in the file: [lab_02](https://github.com/Nemat-Allah-Aloush/Multivariate_Data_Analysis/blob/master/2.Analysis%20of%20multivariate%20random%20variables/lab_02.ipynb)
#### 'Analysis of multivariate random variables'
1. Non-parametric estimation of PDF in form of a histogram and kernel density function.
2. Estimation of multivariate mathematical expectation and variance.
3. Non-parametric estimation of conditional distributions, mathematical expectations and variances.
4. Estimation of pair correlation coefficients, confidence intervals for them and significance levels .
5. Task formulation for regression, multivariate correlation.
6. Regression model,multicollinearity and regularization.
7. Quality analysis.

----------

### The tasks performed in the file: [lab_03](https://github.com/Nemat-Allah-Aloush/Multivariate_Data_Analysis/blob/master/3.Sampling%20of%20multivariate%20random%20variables/lab_03.ipynb)
#### 'Sampling of multivariate random variables'
1. Substantiation of chosen subsample.
2. Sampling of chosen target variables using univariate parametric distributions with 2 different sampling methods.
2.1. Inverse transform sampling.
2.2. Accept-Reject Sampling.
3. Estimation of relations between predictors and chosen target variables.
4. Bayesian networks.
4.1. Manual Bayesian network.
4.2. Structural learning model: Hill-Climbing with K2 score function.
4.3. Structural learning model: Search strategy PC algorithms with MI score function.
5. Quality analysis.

-----------

### The tasks performed in the file: [lab_04](https://github.com/Nemat-Allah-Aloush/Multivariate_Data_Analysis/blob/master/4.Stationarity%20of%20the%20processes/lab_04.ipynb)
#### 'Stationarity of the processes'
1. Substantiation of chosen sampling.
2. Stationary analysis.
3. Covariance or correlation function analysis.
4. Noise filtration.
5. Estimation of spectral density function.
6. Auto-regression model.
6.1 Train a SARIMA model with the values of variable (T2).
6.2 Train a SARIMA model with the filtered values of variable (T2).
6.3 Train a SARIMA model with the values of variable (T_out).
6.4 Train a SARIMA model with the filtered values of variable (T_out).
7. Model in a form of linear dynamical system.
