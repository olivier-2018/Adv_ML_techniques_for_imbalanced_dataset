# FHNW Data Science specialization module
## Advanced Machine Learning techniques for imbalanced datasets
=======

## Project requirements:
- Develop a classifier for the adult census dataset using advanced machine learning techniques

### Dataset:
- https://archive.ics.uci.edu/ml/datasets/Adult

### Getting started:
- Install a virtual environment:
```sh
virtualenv -p /usr/bin/python3.10 venv
```
- Activate virtual environment:
```sh
source venv/bin/activate
```
- Install python libraries:
```sh
pip install -r requirements.txt
```
- Clone the repository:
```sh
git clone git@github.com:olivier-2018/Adv_ML_techniques_for_imbalanced_dataset.git
# then
cd Adv_ML_techniques_for_imbalanced_dataset
```
- Run the jupyter notebook using your favorite IDE.


## Results overview:

### Data exploration - Numerical features
![Numerical features](assets/numerical_features.png)

### Data exploration - Categorical features
![Categorical features](assets/categorical_features.png)

### Pipeline & customer transformers
![pipeline](assets/pipeline.png)

### Raw features cross-correlation
![Raw features](assets/raw_features_cross_correlation.png)

### Transformed features cross-correlation
![Engineered features](assets/transformed_features_cross_correlation.png)

### Feature importance
![Feature_importance](assets/feature_importance.png)

### Final classification
![Classification](assets/final_classification.png)

### Precision-Recal & ROC_curves
![Precision-Recal](assets/PR+ROC_curves.png)
