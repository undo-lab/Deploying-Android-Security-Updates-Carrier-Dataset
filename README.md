# Deploying-Android-Security-Updates-Carrier-Dataset
This repository contains raw data collected from the top 4 U.S. mobile carriers and Jupyter notebooks to normalize and visualize this data as used in "Deploying Android Security Updates: an Extensive Study Involving Manufacturers, Carriers, and End Users"

*** 

## Folder Directory
#### data
Contains all datasets in this work such as the raw updates programatically collected from the U.S. mobile carriers, normalization outputs, and year certain device models were released.

#### normalization
Contains three Jupyter Notebooks intended to be executed in the numerical fashion. These notebooks normalize the raw updates collected from the carriers as well as ingest the manually collected model release years, Android security bulletin release dates, Android security bulletin CVEs, and more. Data files are output in data through certain normalization steps.

#### visualizations
After executing all three Jupyter Notebooks located in normalization, these notebooks access the resulting data file. Automatically, visualizations are created based on the data file's output such as generic statistics, number of updates per carrier, update frequency for each device model, correlation coefficient between update delay and certain contents in the updates, comparing Samsung locked and unlocked models, calculating the update delay, and calculating the updates over time.  

*** 

## Prerequisites
In order to normalize and visualize, these Jupyter notebooks require the following:
* Python 
* Anaconda (includes Jupyter notebooks and other libraries such as pandas, numpy, and matplotlib)
* Plotly (for interactive visualizations)
* Orca (for saving the interactive visuals)
* Reserachpy (Calculating correlation coefficient)
