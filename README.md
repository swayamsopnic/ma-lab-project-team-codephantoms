# MA Lab Project • CodePhantoms

## Introduction

This repository encapsulates our team’s **Weather Forecasting Machine Learning solution** — a data-driven ML workflow built around real meteorological data from Seattle and inspired by established Kaggle weather-prediction frameworks. The goal is not just prediction — but actionable forecasting insights through scalable, interpretable models.

---

## Project Objective

Enable reliable short-term weather predictions using historical weather patterns. This repository demonstrates:  
- **Data ingestion & preprocessing**  
- **Exploratory Data Analysis (EDA)**  
- **Feature engineering**  
- **Machine Learning modeling & evaluation**  
- **Prediction** and insight extraction

The reference implementation is grounded in the *Weather Prediction* Kaggle notebook by Gokul Prasanth — proven and modular approach to building predictive weather models. :contentReference[oaicite:0]{index=0}

---

## Stack & Technologies

| Category | Tools / Libraries |
|----------|------------------|
| Data Manipulation | Python, Pandas, NumPy |
| Modeling | scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Notebook | Jupyter |

> Designed for seamless extension — support for deep learning frameworks or APIs can be added modularly.

---

## Key Features

### Data Pipeline
- Format, clean, and validate time-series weather data
- Handle missing values and normalize distributions

### Machine Learning
- Train models on meaningful features like temperature, humidity, wind, etc.
- Evaluate using standard metrics (e.g., RMSE / accuracy)

### Insights & Interpretation
- Model performance metrics
- Visual comparisons between predictions vs ground truth
- Feature importance analysis

---

## How to Use

### Clone Repository

```bash
git clone https://github.com/swayamsopnic/ma-lab-project-team-codephantoms.git
cd ma-lab-project-team-codephantoms

```

## ▶ After Cloning the Repository

This section outlines the complete post-clone execution workflow — from environment setup to model execution and result validation.

---

## Navigate to the Project Directory

Move into the cloned repository:

```bash
cd ma-lab-project-team-codephantoms
```

---

## Verify Python Environment

Ensure Python is installed and meets the minimum version requirement.

```bash
python --version
```

Recommended: Python 3.8 or higher

---

## Create a Virtual Environment (Best Practice)

Create an isolated Python environment to ensure dependency stability.

```bash
python -m venv venv
```

Activate the virtual environment:

### Linux / macOS
```bash
source venv/bin/activate
```

### Windows
```bash
venv\Scripts\activate
```

---

## Upgrade pip (Optional but Recommended)

```bash
pip install --upgrade pip
```

---

## Install Project Dependencies

Install all required libraries used for data processing, visualization, and machine learning.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## Launch Jupyter Notebook Server

Start the Jupyter Notebook interface:

```bash
jupyter notebook
```

---

## Open the Project Notebook

From the Jupyter interface, open:

```
weather-prediction.ipynb
```

---

## Execute the Notebook

Run all cells top to bottom to ensure correct execution flow.

---

## Dataset Handling

The dataset `seattle-weather.csv` is already included in the repository.  
No external download is required.

---

## Output & Results

After execution, the notebook generates:
- Cleaned dataset
- Trained ML models
- Prediction results
- Performance metrics
- Visual analytics

---

## Troubleshooting

If issues occur:
- Ensure virtual environment is activated
- Restart kernel and rerun all cells

```bash
pip install --force-reinstall pandas numpy scikit-learn
```

---

## Execution Complete

The weather prediction pipeline is now fully operational locally.
