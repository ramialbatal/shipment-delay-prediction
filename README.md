# Shipment Delay Prediction

This repository contains two notebooks focused on analyzing and predicting shipment delays using GPS data and shipment bookings. The environment is managed using `pipenv`, and the `Pipfile` and `Pipfile.lock` are included in the repository for easy setup.

## Setting up the Environment

To set up the environment and install all the necessary dependencies, please follow these steps:

1. Ensure you have `pipenv` installed. If you don't have it installed, you can install it by running:

```bash
pip install pipenv
```

2. Clone the repository to your local machine and navigate to the project directory.

```
git clone git@github.com:ramialbatal/shipment-delay-prediction.git
cd shipment-delay-prediction
```

3. Use pipenv to install the required packages listed in the Pipfile:

```
pipenv install
```
4. Activate the virtual environment:
```
pipenv shell
```

## Using the Notebooks
Once the environment is set up, you can run the two notebooks in the repository:

1. Open Jupyter by running the following command inside the activated pipenv environment:

```jupyter notebook```

2. From the Jupyter interface, you can access and run the notebooks available in the repository

## Dependencies

The environment uses Python 3.8, and the following key packages are installed:

* pandas
* requests
* geopy
* matplotlib
* seaborn
* scikit-learn
* imbalanced-learn
* xgboost

Development packages include ipykernel for Jupyter notebook support.