# BME 304 Final Project: Uncertainty in Urinary Biomarker Classification of Early Pancreatic Cancer

Rosalyn Morin (rm523), Daniel Elsharkawy (dae31)

## Research question
Can predictive uncertainty estimates identify unreliable classifications of early-stage
pancreatic cancer from urinary biomarkers, particularly when distinguishing cancer from
benign hepatobiliary disease?

## Data
S1 Table from Debernardi et al., *PLOS Medicine* (2020), doi: 10.1371/journal.pmed.1003489.

## Repository structure
```
data/
  Debernardi et al 2020 data.csv            # 590 urine samples (raw data)
  Debernardi et al 2020 documentation.csv   # description of each column
notebooks/
  PancRISK_Uncertainty_Analysis.ipynb       # analysis notebook
docs/                                       # proposal and final report
```

## How to run
1. Install the packages: `pip install pandas numpy scipy scikit-learn matplotlib`
2. Open `notebooks/PancRISK_Uncertainty_Analysis.ipynb` and run the cells from top to bottom.
   The notebook reads the data from `../data/`, so keep the folder structure as shown above.
