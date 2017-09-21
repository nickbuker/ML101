# Introductory discussions of machine learning topics

#### About the project and notebook contents
These notebooks are intended to be simple and fun introductions to basic machine learning concepts and techniques. I have created them for my employer Nordstrom.

##### ML101_1.ipynb
* **Define machine learning**
* **Discuss estimation and cost/loss functions**
* **Some common syntax and conventions for data**
* **General types of machine learning**
* **Where to find data**
* **Loading data and initial inspection**
* **Train test splits**
* **Fitting a tree regression model**
* **Bias/variance trade-off**
* **Overfitting and underfitting**
* **What are hyperparameters and how do we set them**
* **Grid searching and K-fold cross validation**

#### To install
These notebooks are designed to run with Python 2.7. In order to install the requirements, type run following command from the ML101 directory. As always, use of a virtualenv is recommended.

`$ pip install -r requirements.txt`

Once the requirements have been installed, you should be able to launch the notebook by navigating to the notebooks directory and running the command below.

`$ jupyter notebook`

#### Directory Structure
```
ML101
├── data
│   └── model_data.csv
├── notebooks
│   ├── ML101_1.ipynb
│   └── images
├── readme.md
└── requirements.txt
```
