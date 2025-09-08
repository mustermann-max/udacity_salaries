Udacity Saralies prediction

Installation
This project requires Python 3.x and the following libraries:
- pandas
- numpy
- matplotlib
- scikit-learn
- shap

Project Motivation
As someone, who decided to persue a master's degree in computer science mid-career, I was curious to see how much of an impact this would have on my salary. This project aims to explore the factors that influence developer salaries and build models to predict salaries based on these factors.
To achieve this goal, I used data from the Stack Overflow Developer Survey 2025.

File Descriptions
- `Salaries.ipynb`: Jupyter notebook containing the main analysis and modeling code.
- `survey_results_public.csv`: file containing the survey data.
- `README.md`: this file.

Project Findings
The data required significant preprocessing, including handling missing values and encoding categorical variables.
Cutting off outliers and reducing the dataset to only include developers from Germany significantly improved model performance.
Tuning the hyperparameters of the HistGradientBoostingRegressor did not improve performance very much.
An MLPRegressor had surprisingly lower performance than the HistGradientBoostingRegressor, which was the best performing model.
Analyzing the shap values did not reveal that Education has a significant impact on salary.
5 hours is an optimistic estimate of the time required for this project.

Acknowledgements
This project was made for the Udacity Data Scientist Nanodegree program.
Using the Course resources, the documentation of the libraries mentioned above, stack overflow and chat gpt.
