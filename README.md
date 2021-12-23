# Description
This repository contains an analysis on the occurrence of strokes based on anonymized healthcare data. More specifically, it contains a Jupyter notebook that describes various machine learning approaches, including multilayer perceptrons and random forests, to predict strokes based on patient features such as age, body mass index, and smoking status. I decided to analyze this dataset for fun and to improve my classification skills for imbalanced datasets.

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) and is sponsored by [fedesoriano](https://www.kaggle.com/fedesoriano).

# Installation
This repository requires Python 3.6 or higher. To get started, run the following commands:

```
git clone https://github.com/tvdaal/stroke-predictions.git
cd stroke-predictions
conda env create -f environment.yml
conda activate py39-strokes
python -m ipykernel install --user --name py39-strokes --display-name "py39-strokes"
```

The virtual conda environment called 'py39-strokes' contains all necessary packages and dependencies. The last step ensures that the IPython kernel uses the right environment.
