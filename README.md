# USA-Aviation-Accident-and-Incident-MiniProject
Mini Project exploring trends and insights into the last 10 days of USA Aviation Accidents and Incidents

Dataset: FAA (attatched in repository)

The objective of this project was to explore the aviation accident and incident trends over the last 10 days.
Python was used to read, clean, and store a CSV file and NumPy, Pandas, Matplotlib, Seaborn, Plotly, and Cufflinks were used to cluster and visualize data groups.

# Observations: Past 10 days of data

- There were 95 Aviation Accidents and Incidents over the last 10 days.
- Texas, Florida, and California lead the way in A&Is with 10, 9, and 6, respectively.
- There were a total of four A&Is that had fatalities: Florida, Montana, and New York all had two fatalities each and Utah had four fatalities.
- 43.15% of all A&Is happened during the flight's landing phase.
- 68.42% of all A&Is happened during personal flights.
- Hour of the Day and the Amoount of A&I had a R = .55 with a P Val = .02.

# Install
pip install numpy | conda install numpy

pip install pandas | conda install pandas

pip install matplotlib | conda install matplotlib

pip install seaborn | conda install seaborn

pip install plotly

pip install chart-studio

pip install cufflinks

pip install scipy | conda install -c anaconda scipy

# Import
%matplotlib inline

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import chart_studio.plotly as py

import plotly.graph_objs as go 

from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot

init_notebook_mode(connected=True) 

import cufflinks as cf

init_notebook_mode(connected = True)

cf.go_offline()
