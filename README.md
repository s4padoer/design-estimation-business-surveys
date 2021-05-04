# design-estimation-business-surveys

## Computer codes for "Design and Estimation in Business Surveys - Selected Topics" by Patricia Dörr (2020)

This repository contains the computer code for the functions and simulations described in the PhD thesis "Design and Estimation in Business Surveys - Selected Topics" by Patricia Dörr (2020). 

The codes are arranged according to the chapters that the algorithms/ simulations can be found in, which means:

***Multilevel Regression Analysis in Business Surveys (Chapter 2)***

- Monte-Carlo Expectation Maximization algorithm for survey weighted (non-)Gaussian regression models (R Package    wmm   )
- Simulation study for testing the algorithm under (non-)informative survey designs

          
***GVFs in Business Surveys (Chapter 3)*** 

- Simulation study for testing the model-design theory of generalized variance functions (GVFs)

***A Multivariate Probability Density Estimator using SOMs (Chapter 4)***

- Modified and dynamic batch self-organizing map algorithm with adaptive distances GNU GENERAL PUBLIC LICENSE
- Density estimator built upon the modified SOM algorithm
- Simulation study to compare the density estimator to Gaussian mixtures and kernel density estimators

The applications to real world survey data are comprised in an additional folder called ***   application_beeps   *** as the real world data stems from the World Bank's Business Environment and Enterprise Performance Surveys (BEEPS). The data are from Central Asian and Eastern European countries (cf. the thesis for a detailed data set description). The folder includes 

- Application of the MCEM to business survey data (the impact of the business leader's gender on the firm's access to finance)
- Application of the density estimator based on SOMs on the bivariate density of total turnover in the current year and three years ago. The data has the advantage that it assuminglyl correlated and skewed, which imposes challenges to density estimators. 

The folder ***lib*** contains the compilation and source files for the   ***wmm***       R   -package (owner and maintainer: Patricia Dörr), which was created for an easier use of the proposed MCEM algorithm. 

***NOTE:*** Due to a formatting error resulting from an update of the depending    R   -package    lme4   the package does not return correct estimates. A revised package correcting the formatting error is provided. However, for better accountability, the original version is given here as well. 
