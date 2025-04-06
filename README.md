# Drug Discovery Using Machine Learning

This project focuses on applying machine learning techniques in the field of bioinformatics to aid in **drug discovery**. 

The aim is to accelerate the identification of potential drug candidates using predictive modeling, ultimately reducing the cost and time of early-phase drug development.

## Objective

To build and evaluate machine learning models that can predict the bioactivity of chemical compounds against a biological target.

## Project Structure
```bash
├──notebook/
└──CDD_ML_Part_1_bioactivity_data.ipynb                                        # data collection
└──CDD_ML_Part_2_Exploratory_Data_Analysis.ipynb                               # EDA      
└──DD_ML_Part_3_Acetylcholinesterase_Descriptor_Dataset_Preparation.ipynb      # data modelling
└──CDD_ML_Part_4_Acetylcholinesterase_Regression_Random_Forest.ipynb           # machine learning
└──CDD_ML_Part_5_Acetylcholinesterase_Compare_Regressors.ipynb                 # model evaluation+comparison
```

## Dataset

The dataset contains molecular descriptors of various chemical compounds and their corresponding biological activity. It is sourced from public bioactivity databases like **ChEMBL**.

- Features: Molecular fingerprints, physicochemical properties
- Target: Bioactivity classification (Active/Inactive)

## Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## How to Run

**1. Clone the repository**
```bash
git clone https://github.com/veydantkatyal/drug-discovery.git
cd drug-discovery
```

**2. Launch Jupyter Notebook:**
```bash
jupyter notebook
```

**3. Open `notebooks/Drug_Discovery_Model.ipynb` and run the cells.**

## Future Work
- Incorporate deep learning (Graph Neural Networks) for molecular representation

- Use of additional descriptors (e.g., SMILES)

- Hyperparameter tuning with Bayesian Optimization

## Acknowledgements
- ChEMBL for providing the dataset

- RDKit for cheminformatics tools (future integration planned)

## License

This project is open-source and licensed under [MIT License](https://github.com/veydantkatyal/drug-discovery/blob/main/LICENSE)
