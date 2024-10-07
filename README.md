# cancer-multiclass-classification
The goal of this project is to implement multi-class classification to predict cancer genetic mutations in one of 9 categories

## Skills
- Data Cleaning
- Data Preprocessing
- Data Visualization
- Feature Engineering
- Feature Selection
- Model Training
- Model Evaluation
- Model Interpretation

## Technologies
- Python
- Pandas
- Numpy
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

## Data
The data is from Personalized Medicine: Redefining Cancer Prognosis and Treatment. (https://www.kaggle.com/competitions/msk-redefining-cancer-treatment/data. There are two files in this data:
- `trainining_variants.csv` - This data contains information about the genetic mutations in the cancer cells.
- `training_text.csv` - This data contains clinical evidence that human experts/pathologists use to classify the genetic mutation.
- There are nine categories with their corresponding class labels (1 to 9):
    1. Likely loss-of-function
    2. Likely gain-of-function
    3. Neutral
    4. Loss-of-function
    5. Likely neutral
    6. Inconclusive
    7. Gain-of-function
    8. Likely switch-of-function
    9. Switch-of-function

## Project Tasks
1. Loading Data
2. Text Preprocessing
3. Train-test Split
4. Measuring Performance Using Random Model
5. Encode the Features
6. Check Feature Importances
7. Model Training

## Project Structure
```
cancer-multiclass-classification/
├── data/
│   ├── training_variants.csv
│   ├── training_text.csv
├── notebooks/
│   ├── Solution.ipynb
├── README.md
```
