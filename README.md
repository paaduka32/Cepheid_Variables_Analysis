# Overview

This project focuses on using Cepheid variable stars to determine cosmic distances. The analysis aimed to test key hypotheses related to Leavitt's Law, period determination, absolute magnitude estimation, and distance calculations for measuring galaxy distances.
Our findings were presented in a detailed study, and the results demonstrate the accuracy of Cepheid variables as standard candles in astronomy. The project uses observational data, statistical modeling, and Python-based visualization to analyze and interpret the data effectively.

# Hypotheses Tested

### Leavitt's Law Calibration: 
The period-luminosity relationship of Cepheid variables can be determined using regression analysis.
### Period Determination: 
Light curves of Cepheid variables follow a sinusoidal pattern, allowing for accurate period estimation.
### Absolute Magnitude Calculation: 
Absolute magnitudes of Cepheids can be determined from their periods using a linear relation.
### Distance Estimation: 
By combining absolute and apparent magnitudes, we can calculate precise distances to Cepheids.
### Galaxy Distance Measurement: 
The average distance of multiple Cepheids in a galaxy provides an accurate estimate of the galaxy's distance.

# Project Structure

📂 Cepheid-Variable-Analysis

│── 📄 README.md  # Project documentation

│── Analysis.ipynb  # Complete code for analysis

│── cepheids.csv  # organised in two columns: the period of the cepheid variable and its absolute magnitude calculated from mean luminosity.

│── curves.csv  # data of the light curves of many cepheids in the line of sight of a galaxy. The data contains three columns: ID(Unique for every cepheid), JD (the julian date of observation) and the apparent magnitude observed.

# Findings

The period-luminosity relationship was successfully derived using regression analysis.

Period estimation from light curves provided accurate values for Cepheid variables.

Absolute magnitudes and distances were computed with high precision, supporting the validity of Leavitt's Law.

The estimated distance to the target galaxy aligns well with previously published values, confirming the reliability of Cepheid variables as distance indicators.

# Future Work

Refining models: Using more advanced statistical and machine learning approaches for period estimation.

Expanding datasets: Incorporating additional Cepheid observations from missions such as Gaia and Hubble.

Experimental validation: Cross-checking results with independent distance measurement techniques.

# Contributor
[paaduka32](https://github.com/paaduka32)
