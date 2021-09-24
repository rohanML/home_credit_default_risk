Home Credit Default Risk
==============================

To predict clients' loan repayment capability

### Table of Contents

1. Source Data
  	* [Home Credit Risk](https://www.kaggle.com/c/home-credit-default-risk) 
 
2. Documents
  	* [Final Report](https://github.com/rohanML/home_credit_default_risk/blob/master/reports/Predicting%20Credit%20Default%20-%20Report.pdf)
  The report contains a detailed account of the data, data wrangling, EDA, feature Engineering & modeling performed for this project.
  	* [Presentation](https://github.com/rohanML/home_credit_default_risk/blob/master/reports/Home%20Credit%20-%20Presentation.pdf)
  This presentation summarizes objective, data, process and business impact of the project. 
3. Notebooks
	* [Data Description](https://github.com/rohanML/home_credit_default_risk/blob/master/notebooks/00_Data_Description.ipynb)
	* [Data Wrangling](https://github.com/rohanML/home_credit_default_risk/blob/master/notebooks/01_Data_Wrangling.ipynb)
  	* [Exploration Data Analysis](https://github.com/rohanML/home_credit_default_risk/blob/master/notebooks/02_Exploratory_Data_Analysis.ipynb)
  	* [Feature Engineering](https://github.com/rohanML/home_credit_default_risk/blob/master/notebooks/03_Feature_Engineering.ipynb)
  	* [Modelling](https://github.com/rohanML/home_credit_default_risk/blob/master/notebooks/04_Modelling.ipynb)


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
