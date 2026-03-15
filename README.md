# Diabetes Prediction Project

A machine learning project that uses logistic regression to predict diabetes risk based on patient health metrics.

## Overview

This project demonstrates a binary classification approach to diabetes prediction using the scikit-learn diabetes dataset. The regression target is converted into a binary classification problem to determine whether a patient is at high risk (above median) or low risk (below or at median).

## Features

- **Dataset**: Scikit-learn's diabetes dataset (442 samples, 10 features)
- **Features**: Age, sex, body mass index, blood pressure, and six blood serum measurements
- **Model**: Logistic Regression with binary classification
- **Evaluation**: Accuracy score, confusion matrix, and detailed classification report

## Installation

### Prerequisites

- Python 3.7+
- pip or conda

### Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd diabetes-prediction-project
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebook to train the model and view results:

```bash
jupyter notebook Diabetes_Update.ipynb
```

## Project Structure

```
diabetes-prediction-project/
├── Diabetes_Update.ipynb    # Main notebook with model training
├── requirements.txt         # Python dependencies
├── README.md               # This file
└── .gitignore             # Git ignore file
```

## Results

The notebook outputs:
- **Accuracy**: Model performance on test set
- **Confusion Matrix**: True positives, true negatives, false positives, false negatives
- **Classification Report**: Precision, recall, and F1-score per class

## Dependencies

- numpy
- pandas
- scikit-learn

See `requirements.txt` for specific versions.

## Future Enhancements

- Cross-validation for robust evaluation
- Feature scaling and normalization
- Hyperparameter tuning
- Comparison with other models (Random Forest, SVM, etc.)
- Data visualization and exploratory analysis

## License

MIT License

## Contributing

Feel free to fork, submit issues, and create pull requests.
