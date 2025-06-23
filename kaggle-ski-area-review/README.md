# ML-kaggle-on-the-snow-ski-area-reviews

##  Overview

This repository includes code and documentation for conducting a sentiment analysis on onthesnow-ski-area-reviews kaggle dataset. It covers data exploration, preprocessing, and modeling, with the final goal of providing actionable insights from the data.

## Dataset
The dataset used in this repository is from Kaggle. You can access it here [https://www.kaggle.com/datasets/fredkellner/onthesnow-ski-area-reviews.].

##  Get Started

### Install jupyter notebook

https://jupyter.org/install


## Requirements
```
Python 3.x
pandas
numpy
matplotlib
seaborn
tbd:
```

### Download dataset:

#### Step 1: Get your kaggle API tokens file: kaggle.json<br>
Kaggle API Usage: visit for more details https://github.com/Kaggle/kagglehub
The file should have the following attributes:
```
{"username":"xxxxxx","key":"xxxxxxxxxxxxxxxxxxxxxx"}
```

#### Step 2: Ensure kaggle.json is in the location ~/.kaggle/kaggle.json to use the API.

### Start Jupyter Notebook
In the root directory, run

```
python -m ipykernel install --user --name="skireview" --display-name "skireview"
```
Then run
```
jupyter notebook
```

In each notebook, select the kernel to be skireview

##  Usage

Use the following ipynb file to import the data and conduct data exploration
```
data_import_and_exploration.ipynb
```

Use the following ipynb file to preprocess the data 
```
data_preprocessing.ipynb
```

Use the following ipynb file to train the model 
```
model_training.ipynb
```

## Contributing

Hayley luo
