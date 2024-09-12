# Made-With-ML
An MLOps best practice and project respository.

## Initialisation

### Setup
It is recommended to use Python 3.10.11. YOu can use pyenv (https://github.com/pyenv-win/pyenv-win) to control for environments in your system.
If using pyenv environment, use the following steps at your directory of choice to initialise a Python environment (using CommandPrompt):

* python3 -m venv venv   _#create virtual environment_
* venv\Scripts\activate  _#activate environment_
* python3 -m pip install --upgrade pip setuptools wheel _#install and upgrade pip to the latest version_

### Install Packages and Get Started
Within the new environment, install necessary libraries using the 1st step below and then get started with a Jupyter notebook using the following step:
* python3 -m pip install -r requirements.txt
* jupyter lab notebooks/madewithml.ipynb

I build this repo with the help of [madewithml](https://madewithml.com/#course) course by Goku Mohandas. The latest repo of this course can be found at [Made-With-ML.git](https://github.com/GokuMohandas/Made-With-ML).
