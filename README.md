# vivino-analysis

- Open notebook in github: [Vivino_wine_analysis_Sansar_Choinyambuu.ipynb](Vivino_wine_analysis_Sansar_Choinyambuu.ipynb)
- Open notebook in colab: [Vivino_wine_analysis_Sansar_Choinyambuu.ipynb](https://colab.research.google.com/github/sansar-choinyambuu/vivino-analysis/blob/master/Vivino_wine_analysis_Sansar_Choinyambuu.ipynb)


The purpose of this analysis to find out the most important features that influence how people rate wines. Data used in this analysis was scraped from vivino.com using self written API client available at: https://github.com/sansar-choinyambuu/vivino-scraper

The following tasks are done within this analysis:
- data extraction
- exploratory analysis
- data preparation pipeline using ColumnTransformer from sklearn
- training all classifiers available in sklearn
- hyperparameter tuning on selected classifier - LogisticRegression
- training simple neural network classification model
- model analysis via confusion matrix
- feature importance analysis
  - via coefficients of logistic regression
  - via PCA
