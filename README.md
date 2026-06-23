# DFN-Kcr
This repository contains the source code and resources for **DFN-Kcr**

## Environment Setup
conda create -n dfn-kcr python=3.10
conda activate dfn-kcr
pip install -r requirements.txt

## Project Structure
  - datasets/ — Training and test datasets.
  - models/protein_bert/ — Pre-trained ProteinBERT weights.
  - code.ipynb — Main implementation of DFN-Kcr.
  - environment.yml — Conda environment specification.
  - requirements.txt — Python package dependencies.

## Model Weights
Due to file size limitations, pre-trained weights are hosted externally:<a href='https://drive.google.com/file/d/1WwdCJbnk0RAxdPA_QqNqxhq3IEN2dHB-/view?usp=sharing'>ProteinBERT</a>. 
<br>Please download the file, create the directory models/protein_bert/, and place the model weights there.

## Usage
Open code.ipynb in Jupyter Lab or Jupyter Notebook and run the cells sequentially.

## Notes
Ensure the ProteinBERT weights are placed in models/protein_bert/ before running the code.
Place the datasets in the datasets/ directory.
