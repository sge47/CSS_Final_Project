## Purpose of Repository

This repository includes an analysis of data from the 100,798 cases of firearm deaths documented in the `gun_deaths` dataset from the rcis library, sourced from [Five Thirty Eight](http://fivethirtyeight.com/features/gun-deaths/). The dataset includes records on all firearm deaths in the United States from 2012 to 2014. This repository includes code for a project that investigates the effect of demographic information on the likelihood of one dying by firearm, looking specifically at firearm deaths involving police officers and suicide.

## Files Necessary

- css_final_project.Rmd
  - This file contains the code for the cleaning and analysis of the `gun_deaths` dataset shown through seven plots.
- category_plots.Rmd
  - This file contains five additional plots analyzing the `category` variable I created that combines age group and intent behind gun deaths.
- css_final_project_files/
  - This file contains the plots from the analysis of the `gun_deaths` dataset within the css_final_project.Rmd file.
- category_plots_files/
  - This file contains the plots from the analysis of the `gun_deaths` dataset within the category_plots.Rmd file.
- clean_gun_deaths.csv
  - This file contains the cleaned `gun_deaths` data, which involved the recoding of the `police` variable and the creation of a the aforementioned `category` variable.

## Required Packages

You will need to load the tidyverse and rcis libraries.


