# Movie Revenue Prediction

## Overview
This project focuses on predicting the revenue of movies based on their budgets using K-nearest neighbors regression. The goal is to provide investors and directors with a tool to estimate potential profits from their film projects before release.


## Project Authors
- Ming Zhang
- Rehan Mondal
- Caroline Lu
- Jingwen Leng

  
## Data Source
The dataset used is the "TMDB 5000 Movie Dataset" from Kaggle, which includes details on revenues, budgets, and other attributes for 5000 movies. The dataset can be accessed [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

## Dependencies
This project is implemented in R, using libraries from the tidyverse for data manipulation and ggplot2 for visualization. The `tidymodels` framework is utilized for creating and evaluating the machine learning model. Ensure the following R packages are installed:
- tidyverse
- tidymodels
- GGally
- infer
- cowplot

You can install these packages using the following R command:
```R
install.packages(c("tidyverse", "tidymodels", "GGally", "infer", "cowplot"))
