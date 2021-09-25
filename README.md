# Udacity-Data-Analysis-Professional

# I - Introduction to data analysis

## 1- Jupyter notebook

### What is Jupyter notebook

Jupyter notebook allows you to combine text, code, visualisation and more in one place, it is a web application.

### Installing Jupyter

The Jupyter notebooks automatically get installed with the Anaconda distribution. You'll be able to use notebooks from the default environmen.

```
# First, verify if you have Python and conda installed
# If the command below shows an error, try installing it first using `conda install python=3`
python --version
conda --version

# Use either of the commands below to install notebook
conda install jupyter notebook
conda install -c conda-forge notebook
```

To run the notebook, run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows) / Anaconda Prompt (Windows):
```
jupyter notebook
```

### Launching the Notebook Server

Go to path from cli and run this code

```
jupyter notebook
```

To add conda tab to Jupyter

```
conda install nb_conda
```

## 2- The data analysis process

Data analysis helps in predection and taking decisions, for example Walmart use it to know what items to stock

### Steps for data analysis process

We organized the data analysis process into five steps: Question, Wrangle, Explore, Draw Conclusions, and Communicate. Below is a review of the key points, but feel free to move ahead. We will practice each step as we go through the next sections, and you will get the whole process down in no time.

**Step 1: Ask questions**
Either you're given data and ask questions based on it, or you ask questions first and gather data based on that later. In both cases, great questions help you focus on relevant parts of your data and direct your analysis towards meaningful insights.

**Step 2: Wrangle data**
You get the data you need in a form you can work with in three steps: gather, assess, clean. You gather the data you need to answer your questions, assess your data to identify any problems in your data’s quality or structure, and clean your data by modifying, replacing, or removing data to ensure that your dataset is of the highest quality and as well-structured as possible.

**Step 3: Perform EDA (Exploratory Data Analysis)**
You explore and then augment your data to maximize the potential of your analyses, visualizations, and models. Exploring involves finding patterns in your data, visualizing relationships in your data, and building intuition about what you’re working with. After exploring, you can do things like remove outliers and create better features from your data, also known as feature engineering.

**Step 4: Draw conclusions (or even make predictions)**
This step is typically approached with machine learning or inferential statistics that are beyond the scope of this course, which will focus on drawing conclusions with descriptive statistics.

More on machine learning: Machine Learning Engineer Nanodegree

**Step 5: Communicate your results**
You often need to justify and convey meaning in the insights you’ve found. Or, if your end goal is to build a system, you usually need to share what you’ve built, explain how you reached design decisions, and report how well it performs. There are many ways to communicate your results: reports, slide decks, blog posts, emails, presentations, or even conversations. Data visualization will always be very valuable.