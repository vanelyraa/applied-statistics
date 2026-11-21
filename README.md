# Assesment Submission Applied Statitics

## Table of Contents
 - [Project Purpose](#project-purpose)
 - [Setup Instructions](#setup-instructions)
 - [Install Dependencies](#install-dependencies)
 - [Implementations](#implementations)
    - [Problem 1](#problem-1)
    - [Problem 2](#problem-2)
    - [Problem 3](#problem-3)
    - [Problem 4](#problem-4)


## Project Purpose
This repository contains my submissions for the Applied Statistics module completed as part of the Higher Diploma in Science in Computing in Data Analytics at ATU.
This project is written in Python, in a single file called [problems.ipynb](#problems.ipynb)
The purpose of this assessment is to apply statistical methods to analyse data, create visualisations and explain the results.
The Iris dataset is used for the problems. It contains measurements of 150 flowers from three species: Setosa, Versicolor and Virginica.

## Install Dependencies

All required libraries are listed in requirements.txt  


## Setup Instructions

Clone this GitHub repository:
<pre> git clone https://github.com/vanelyraa/applied-statistics.git</pre>

Navigate the project directory:
<pre> cd https://github.com/vanelyraa/applied-statistics.git </pre>

Create a virtual environment (optional):
<pre> python3 -m venv venv </pre>

Activate virtual environment (optional):  
For windows: <pre> venv\Scripts\activate </pre> 
For MacOS: <pre> source venv/bin/activate  </pre> 

Install required dependencies:
<pre> pip install -r requirements.txt </pre>

Start Jupyter Notebook:
<pre> jupyter notebook problems.ipynb </pre>


## Implementations

#### Problem 1 Exploring Petal Length: 
In this problem I investigate the distribution of petal lengths in the Iris dataset. I created a histogram showing the petal lengths of all 150 flowers, with a normal distribution using the mean and standard deviation calculated from the data.
I also created separate histograms for Setosa, Versicolor and Virginica, each with its own normal distribution.
The mean and standard deviation were calculated for the dataset and each species.

#### Problem 2 Correlation Between Petal Length and Petal Width: 
In Problem 2 I investigat the relationship between petal length and petal width in the dataset.I calculate the Pearson correlation coefficient for all 150 samples and for each species.
I created scatter plots to visualise the relationship between the two measurements, with fitted straight lines using NumPy.
The results show a very strong positive correlation for the complete dataset, but the correlation is different within each species.Versicolor has the strongest correlation between the individual species, while Setosa and Virginica have weaker correlations.

#### Problem 3: 

#### Problem 4: 
** End **

