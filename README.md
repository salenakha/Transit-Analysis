# Transit System Quality Classification

A collaboratively-built classifier for transit systems in four major US cities.


## Project Overview
College graduates often overlook transit quality when relocating for their first job, but it's a major factor affecting affordability, lifestyle, and financial 
independence, especially when deciding whether to own a car or rely on public transportation.

This project analyzes transit data from Boston, New York, Chicago, 
and San Francisco to classify cities as "Transit-Rich" or "Transit-Limited" using machine learning.

**Key Result**: Logistic regression classifier achieving 74.28% accuracy (ROC-AUC: 0.730)

## Structure
- `notebooks/` - Jupyter notebooks with complete analysis (run in order 01 → 02 → 03)
- `data/` - Processed transit dataset (1,855 routes)
- `reports/` - Analysis as a collaboratively written report

## Setup
```bash
pip install -r requirements.txt
jupyter notebook
```

Start with `notebooks/01_proposal_data_collection.ipynb`

## Technologies
- Python, pandas, numpy, scikit-learn
- Data source: Transit.land REST API
```
