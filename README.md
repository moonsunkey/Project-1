Turkish Horse Racing Data Analysis - January 2024



Project Overview:

This project aims to analyze Turkish horse racing data for the month of January 2024 to derive insights and patterns from the races. The analysis primarily utilizes the Python programming language, with the Pandas library for data manipulation and analysis, and Matplotlib for data visualization.

Dataset:
website: https://www.kaggle.com/datasets/sanlian/turkiye-horse-racing-january-2024-race-results/
The dataset used in this analysis consists of Turkish horse racing data for January 2024. It includes various attributes such as race date, race track, horse names, jockey names, race distances, race results, betting odds, and more. 

Analysis Objectives: Looking for insights of horse racing outcomes in terms of breeds, jocky, type, sex, starting box numbers, as well as general information such as races per cities.


Tools Used:

Python: Programming language used for data analysis.
Pandas: Python library for data manipulation and analysis.
Matplotlib: Python library for data visualization.
API: 
Please obtain geopify API key using this link : https://myprojects.geoapify.com/projects and add your API key to an api_keys.py file where geoapify_key = 'Your key here!'

Files Included:
HorceRacing_final.ipynb
clean.csv
Resources folder 
Output folder
Turkish Horse Racing Analysis presentation PDF
README

Instructions for Running the Analysis:
Import dependencies: 
import matplotlib.pyplot as plt
import pandas as pd
import requests 
import hvplot.pandas
from api_keys import geoapify_key

Contributors:
Alyssa Chand
Brian Lee
Jinlu Wang
Rontiff Ha
Zoe Bennett


Acknowledgments:

We acknowledge the providers of the Turkish horse racing data for January 2024, sanlian Anil, which forms the basis of this analysis. We also thank the open-source community for developing and maintaining the tools and libraries used in this project.