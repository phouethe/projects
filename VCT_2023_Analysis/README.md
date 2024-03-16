# Project Overview

This is an analysis of the Valorant Champions Tour (or VCT) tournament series over 2023. Using data gathered from [vlr.gg](https://www.vlr.gg/) which was put into a 
[dataset from Kaggle user 'ediashtarevin'](https://www.kaggle.com/datasets/ediashtarevin/vct-champions-2023-stats), I also added additional information about 
player peripherals which was scraped from [prosettings.net](https://prosettings.net/lists/valorant/). After cleaning and merging these datasets properly, they
were ready for use in Tableau.

The full data viz is on [Tableau Public](https://public.tableau.com/app/profile/ethenh.phouybanhdyt/viz/ValorantVCT2023Presentation/Presentation).

**Project Steps**

* Gather both player data as well as scrape peripheral data
* Clean up and merge datasets
* Upload into Tableau
* Analyze data in order to find relevant or interesting statistics
* Create Tableau presentation

File Overview:
* `webscraping.ipynb` - Downloaded peripheral table from prosettings.net
* `datacleaning.ipynb` - Cleaned and merged datasets into one file

## Programs Used

This project used the following programs:
* JupyterLab
* Python 3.12+
* Python packages
    * pandas
    * selenium webdriver
* Tableau Public
