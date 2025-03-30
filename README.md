# AIML Pokemon Mega Evolution Classification

## Overview
This project utilizes machine learning to classify whether a Pokémon is a Mega Evolution based on its statistical attributes. The dataset used is from Kaggle: [Pokemon Dataset](https://www.kaggle.com/datasets/abcsds/pokemon/data).

## Objective
The goal is to build a machine learning model that can determine if a Pokémon is a Mega Evolution without using its name as a feature. Instead, the classification is based on attributes like HP, Attack, Defense, etc.

## Features Used
- Total
- HP
- Attack
- Defense
- Special Attack (Sp. Atk)
- Special Defense (Sp. Def)
- Speed

## Model
- Logistic Regression was used for classification.
- Model performance was evaluated using:
  - Confusion Matrix
  - ROC Curve
  - Precision-Recall Curve

## Output
The final output is saved in a CSV file (`model.csv`) with the following columns:
- **Pokemon**: The name of the Pokémon.
- **Mega_Evolution**: `Yes` if it is a Mega Evolution, `No` otherwise.

## Results
Generated plots include:
- Confusion Matrix (`confusion_matrix_logisticreg.png`)
- ROC Curve (`roc_curve_logisticreg.png`)
- Precision-Recall Curve (`prc_logisticreg.png`)

## Running the Project
1. Load the dataset (`Pokemon.csv`).
2. Train-test split the data.
3. Train the Logistic Regression model.
4. Generate predictions and evaluate the model.
5. Save the predictions in `model.csv`.

## Dependencies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Repository Structure
```
├── AIML_Pokemon.ipynb   # Jupyter Notebook with implementation
├── model.csv            # Final classification results
├── confusion_matrix_logisticreg.png
├── roc_curve_logisticreg.png
├── prc_logisticreg.png
├── README.md            # Project documentation
```

## Acknowledgments
Dataset sourced from Kaggle: [Pokemon Dataset](https://www.kaggle.com/datasets/abcsds/pokemon/data).


