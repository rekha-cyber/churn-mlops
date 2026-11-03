# churn-mlops

## Project Description
This project develops and trains a machine learning model using Python and scikit-learn. It includes data processing, model training, and model evaluation.

## Technologies
- Python 3.14.7
- pandas
- scikit-learn
- joblib

## Setup

Clone the repository:
```bash
git clone <repo-url>
cd <repo>
```

Create and activate a virtual environment:

**Windows:**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Mac/Linux:**
```bash
python -m venv .venv
source .venv/bin/activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Run the Project

Train the model:
```bash
python train.py
```

Check the model:
```bash
python check_model.py
```