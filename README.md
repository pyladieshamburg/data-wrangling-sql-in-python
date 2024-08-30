# SQL in Python


![SQL Python Jupyter](https://blog.jetbrains.com/wp-content/uploads/2022/02/Blog_Featured_image_1280x600-2-1.png)

SQL is a very important language for working with data. People who can write both SQL and Python can work across a
broader spectrum in the data world. How does SQL
combine with python?

In this workshop we will be using Fugue and DuckDB and practice manipulating data using SQL.


### Start here:

🍴Fork this repo!

## Setup

Requirements:
- python > 3.10 

If you use environments, do make a new environment and activated it. Then install the libraries:

macos/linux:

```python3 -m pip install -r requirements.txt```

win:

```py -m pip install -r requirements.txt```

GITPOD!

Alternatively you can create an account on [gitpod](https://www.gitpod.io) and use gitpod for the workshop.
- created a gitpod account (you can select github to authenticate)
- create new workspace and paste the link of this repo (or to your fork if you forked it)
- chose your editor, can also use the browser version
- open vscode from gitpod, and follow all the prompts (you need to have vscode installed locally). Alternatively, if you are a pycharm user, open that.
- local: open ssh with token, install the libraries with ```pip install -r requirements.txt```
- browser: activate ipykernel, create a new environment (```python -m venv .venv```), activate it (```pyenv .venv/bin/activate```) and install requirements (```pip install -r requirements.txt```) and select the environment as notebook kernel.


## Problem:
 Our data science team needs features for predicting the customer life time value. The features they've asked for are recency, frequency and monetary value.

 Data is in the data folder in different formats. Open the notebooks below to get the features with 2 different approaches.

### Notebooks:
- [Intro-sql-in-python with Fugue SQL](Intro-sql-in-python.ipynb)
- [Intro-creating-tables with DuckDB](Intro-creating-tables.ipynb)
