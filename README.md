# Credit Risk Prediction App

A machine learning project that predicts whether a loan applicant has **Good** or **Bad** credit risk using the German Credit dataset.

## What This Project Includes

- Data exploration notebook: `analysis_model.ipynb`
- Trained model artifact: `extra_trees_credit_model.pkl`
- Saved encoders for categorical features
- Streamlit web app: `app.py`

## Tech Stack

- Python
- pandas, NumPy
- scikit-learn
- Streamlit

## Project Structure

```text
.
├── app.py
├── analysis_model.ipynb
├── german_credit_data.csv
├── requirements.txt
├── extra_trees_credit_model.pkl
├── Sex_encoder.pkl
├── Housing_encoder.pkl
├── Saving accounts_encoder.pkl
├── Checking account_encoder.pkl
└── target_encoder.pkl
```

## Run Locally

1. Create and activate a virtual environment.
2. Install dependencies.
3. Launch Streamlit.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m streamlit run app.py
```

## App Inputs

The app takes:

- Age
- Sex
- Job category
- Housing type
- Saving accounts category
- Checking account category
- Credit amount
- Duration (months)

And returns the predicted credit risk label.
