Module 7 Challenge

Desription:

In this challenge I used Raw SQL Queries to read data and create tables which ultimately lead me to analyze ETF Portfolios. I then deployed the Jupyter Notebook I did this analysis in as a web application.

Details:

These are the libraries I imported in and then the process of setting up the engine that interacts with SQLite database:

![screenshot1]()

Next using an SQL querie, a DataFrame was created with all the data from the PYPL asset for analysis

![screenshot2]()

After some work, the cumulative returns for PYPL was found. It was then illustrated in this interavtive line plot

![screenshot3]()

To begin analyzing all of the assets in the portfolio, a dataframe with all of the asset's tables was created with an SQL query

![screenshot4]()

These asset's were then analyzed and the cumulative returns were plotted, this is that illustartion deployed in a web application:

![screenshot5]()