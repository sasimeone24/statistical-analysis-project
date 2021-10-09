<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# statistical-analysis-project --- Soccer Price Predictions
*Samuel Simeone Sanchez*

*DAFT-MX-2021/10/08*

## Content
- [Project Description](#project-description)
- [Instructions](#instructions)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The goal of this project is to practice statistical analysis using the iterative data analysis process. In addition, predictive models such as linear regressions, Ridge and LASSO were used.

## Instructions
- Select a dataset from a public source.
- Create a jupyter notebook where the iterative data analysis process is carried out (cleaning, analysis, EDA, visualization and predictive models).
- The objective of the analysis is to identify the most important characteristics of the data obtained. For this, it is necessary to understand the data and study it in depth. In order to finally make a predictive model

## Workflow
- The first step was to find a dataset.
- The second step consisted of understanding the data, in order to know how to proceed when cleaning.
- The distributions of our data are analyzed. I realized that our dependent variable has an exponential distribution so a logarithmic transformation was performed.
- The variables that had a greater correlation with our price variable were searched.
- A linear regression of LASSO was performed.
- Subsequently, linear regressions were performed to verify that all our independent variables had a p-value less than 0.05. If this were not the case, these variables were eliminated from the model since they did not add anything to the model.
- The R2 of our model was obtained.
- It was verified that the distribution of our errors was normal, which was the case.
- The percentage increase in the price of the soccer player was obtained for each of our independent variables.
- The notebook was ordered. Comments were placed on the lines of code and the presentation was made.

## Organization
In the repository we have the Player_Value_Prediction file, which is the python file where the entire process already described above is found (cleaning, analysis, EDA, visualization and predictive models). On the other hand, we have the data folder, where our data files (.csv) are located. Additionally, there is the club.xlxs file which was made by me. Finally, the picture folder is where the images of the graphs obtained are found.

In the links section you will find a great variety of resources that were used to carry out the project.

## Links
[Repository](https://github.com/)

[Database](https://www.kaggle.com/stefanoleone992/fifa-22-complete-player-dataset?select=players_21.csv)

[LASSO, Ridge](https://www.cienciadedatos.net/documentos/py14-ridge-lasso-elastic-net-python.html)

[Q-Q Plot](https://towardsdatascience.com/q-q-plots-explained-5aa8495426c0)

[Logaritmic Transformation](https://medium.com/@kyawsawhtoon/log-transformation-purpose-and-interpretation-9444b4b049c9)

[Power of Ridge Regression](https://towardsdatascience.com/the-power-of-ridge-regression-4281852a64d6)

[Lineal Regression](https://www.cienciadedatos.net/documentos/py10-regresion-lineal-python.html)