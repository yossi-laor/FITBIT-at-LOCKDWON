# FITBIT-at-LOCKDWON
This little project is a result of the Covid-19 lockdown in the UK. 
Swimming pools were shut down, so my favourite activity of swimming and timing laps is impossible. 
As a substitute, I used the activity tracker Fitbit Inspire HR to time cycling and walking.
The data is my heart-rate json files during this year. I find out that repeating short 
cycling intervals is the most energetic type of activity, but that I didn't do it much. 

The Jupyter notebooks are as follows:

JSON-to-DF  -- process the JSON files that Fitbit gives and creates 'activity' dataframes and summaries; these are stored as pickle files

Summary-plot -- plots some of the summary statistics of the activities

Heartrate-plot -- plots the full heart rate for some interesting activities

Interval-cycling -- tries to identify cycles in order to identify the 'best' activities; work in progress

Sandbox -- tries a few methods to identify cycles in the activity heart rates

In addition these are data files:

Data.zip -- the original JSON files from Fitbit, read by the JSON-to-DF notebook
PKL.zip -- the output of the JSON-to-DF notebook which is used as input by the other notebooks



