# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation - Rithvik Neti

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

## Overview

Build a **content-based recommendation system** that, given a **short text description** of a user’s preferences, suggests **similar items** (e.g., movies) from a small dataset. This challenge should take about **3 hours**, so keep your solution **simple** yet **functional**.

### Dataset:

The dataset used in this implementation is from Kaggle called IMDB Movies Dataset. Here is the link to the original data source: https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows. The CSV file for this is loaded into the Github repository, so I can be downloaded from there. Once downloaded locally, it can be run in the Jupyter Notebook given that it is in the same folder. This data contains the top rated movies on IMDB and it is 1000 rows long; however, the code randomly selects 500 to stay within the guidelines of the project.

### Setup:

The Python verison used in this project is Python3, and it is run on a Jupyter Notebook. The requirements for this are in a requirements.txt file, and that needs to be used alongside the Notebook. There is a `pip install -r requirements.txt` command in the Notebook to install the necessary packages and dependencies which are numpy, pandas, and scikit-learn.


### Running:

To open the Jupyter Notebook, you can download the code and run `jupyter notebook Lumaa Project - Rithvik Neti.ipynb` or navigate to it through the file directory. This code is in the form of Jupyter Notebook, and in Jupyter before running the code, one should restart all kernals and then run all cells. This makes sure all variables, libraries, and datasets are loaded correctly. From there, the code will run, and you can input the description to get the top 5 results for movies.


### Results:

The input description in this was "Give me a movie with war and action". The output for this query was the movies 'The Thin Red Line', 'Inglourious Basterds', 'Patton', 'Taegukgi hwinalrimyeo', 'Hotaru no haka'. This is a successful result as all of these movies are war, action, and adventure movies, so these recommendations clearly abide by the prompt.





