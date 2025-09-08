## Household Wealth Prediction with Multi-Class Classification

This project applies multiple machine learning and statistical modeling approaches to predict household wealth status using demographic and economic indicators from the Harvard GLOPOP-S dataset.

The focus is on comparing modern ML algorithms with traditional regression approaches, evaluating their performance, and discussing their applicability in socioeconomic research.

### 📂 Project Structure

* 'main.Rmd' – Main R Markdown file that integrates data preprocessing, model training, and evaluation. Serves as the central workflow for the project.

* 'report.pdf' – Comprehensive report explaining: the origin of the dataset, modeling approaches, results and insights

* 'research_article' – Explanation of the data acquisition and preprocessing from the source (Harvard GLOPOP-S).

* 'functions.R' – A collection of reusable data science functions (contributed by Alexander Rodionov), some of which are adapted in this project.

##### Model-specific outputs:

* 'lgbm.html' – Results of running main.Rmd with LightGBM.

* 'catboost.html' – Results of running main.Rmd with CatBoost.

* 'vglm.html' – Results of running main.Rmd with a Vector Generalized Linear Model (VGLM).

* 'polr10k.html' – Results of running main.Rmd with Proportional Odds Logistic Regression (POLR) on a 10k subset (due to computational constraints).
