# World_Happiness_Project
Exploration of happiness and variables that may be correlated with it.
Link to slide deck presentation - https://docs.google.com/presentation/d/1gk8GpT8jGO5cIRpUUrp5I3RwsM-tqanhbzhGsKwj1nM/edit?usp=sharing
Link to Tableau Dashboard - https://public.tableau.com/app/profile/mel.niere/viz/WorldHappinessProject_16649118490270/UserDashboard

## Project Idea 
Using the survey data from the World Happiness Report, I wanted to see if there were specific variables that were correlated with happiness. 

## Data Cleaning & Processing Part 1 in Excel
I compiled data from 2015 to 2021 from the World Happiness Report from https://www.kaggle.com/datasets/mathurinache/world-happiness-report.
The columns I kept were Country, Region, Happiness Ranking and Happiness Score. I dropped all other columns to keep the data consistent and create my own analytics comparing the variables. 
Each worksheet in the World Happiness Data Compiled Workbook aligns with each year of data. 

## Augmenting Data with additional sources
I wanted to compare World Happiness scores with GDP, Life Expectancy, Unemployment, Safe Water Usage, Sanitation Services, Freedom Scores, and Educational Index. I used data from The World Bank, Agriculture Organization of the United Nations, Freedom House and Wikipedia. 

## Data Cleaning & Processing Part 2 in Excel
I compiled the additional datasets on the World Happiness Data Compiled workbook on separate worksheets, using data from 2015 to 2021 (if available). I had to modify some regions so the World Bank Regions matched the World Happiness Regions. In addition, I had to make minor changes to country names to ensure country naming conventions were consistent. 

I then used VLOOKUP to match the data from the additional datasets to the corresponding countries. Once I merged the datasets together using country names, I copied the information into the workbook World Happiness Static Compiled Clean. 

## Data Exploration with Tableau
I used Tableau to explore the dataset and determine which variables were most correlated with the Happiness Score of a country. I predicted that economic factors like GDP and unemployment would be the most related to happiness, but through exploration I found that I was incorrect! 

## Presentation
I created this presentation to display my finding - https://docs.google.com/presentation/d/1gk8GpT8jGO5cIRpUUrp5I3RwsM-tqanhbzhGsKwj1nM/edit?usp=sharing

I found that happiness was most correlated with life expectancy, education, safely managed drinking water, sanitation services and freedom scores, and least correlated with GDP and unemployment. 

My presentation is an overview of the averages between 2015-2021 and does not look specifically into individual years.

## Extension and Tableau Tool
To further explore this dataset, I created a Tableau dashboard to look at individual regions, countries and years examining the same variables in the datasets. 

Tableau User Dashboard - https://public.tableau.com/app/profile/mel.niere/viz/WorldHappinessProject_16649118490270/UserDashboard

## Sources
Link to World Happiness Report - https://worldhappiness.report/
Link to World Happiness Raw Data - https://www.kaggle.com/datasets/mathurinache/world-happiness-report.
Link to GDP data from World Bank Data - https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
Link to Life Expectancy data from World Bank Data - https://data.worldbank.org/indicator/SP.DYN.LE00.IN
Link to Unemployment data from World Bank Data - https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS
Link to Safe Water Usage and Sanitation Services from Food and Agriculture of the United Nations - https://www.fao.org/faostat/en/#data/FS
Link to Freedom Score from Freedom House - https://freedomhouse.org/countries/freedom-world/scores
Linked Education Index from Wiki (compiled from UNESCO) - https://en.wikipedia.org/wiki/Education_Index
