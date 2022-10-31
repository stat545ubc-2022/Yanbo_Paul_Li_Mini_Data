This repository contains the descriptive and inferential analysis (and output) from the dataset `vancouver_trees`. It is a learning path for using R tidyverse from the beginning to the generation of final output of analysis using libraries including `dplyr`, `ggplot2`, `tidyr`, `broom`, `lubridate`, `readr`, `forcats,` etc.

### **Milestone 1**:

-   I have explored the dataset of `vancouver_trees` by carrying out some descriptive analysis and generating **four potential research questions** for my analysis

-   Along with some graphic processing and summarizing including **kernel density plots, side-by-side bar charts, and boxplots**

### **Milestone 2**:

-   I have narrowed to two research questions by using some functions (e.g. `dplyr` function) to generate **two versions of data** appropriate for my analysis of the two research questions.

-   I have also checked whether my dataset is tidy or not and did some practice by untidying my tidy data and re-tidying back to its original format.

-   To answer one of my research questions on "which height level contains the highest number of trees among which neighbourhood for trees planted between 2000 and 2018", I have modified the plot from milestone 1 by reordering the factor levels of `neighbourhood_names` and `height_level` and also regrouping some levels into broader categories using functions from `forcats`.

-   To answer the other research question on "what is the relationship between height level and tree diameters for trees planted between 2000 and 2018", I have implemented `aov()` which is ANOVA to investigate the relationships (inferential analysis) and produced result summary using `tidy()` in a tibble format from `forcats`.

-   Finally, I have practiced reading and writing csv and rds data by storing a summary table from milestone 1 as a csv file in the newly created `output` folder under my current directory and the ANOVA model object as a rds file in the same folder under the same directory.

To maximize the benefits from learning from this repository, users can expect to get practiced with different functions from different packages listed above and become familiar with them through engagement with a real-life dataset `vancouver_trees` column acquired from *The City of Vancouver's Open Data Portal*. The milestone 1 touches primarily on descriptive analysis, basic graphing and summaries, and milestone 2 touches predominantly on data wrangling, tidying, manipulating for the purpose of inferential statistical analysis and finally saving a new model object in the newly defined `output` folder.

The mini data repo includes three folders including `Milestone 1` (containing the rmd, md files for milestone 1, as well as graph images and `BC_COVID_Cases.csv` dataset (used in part of my preliminary analysis for different datasets) for milestone 1), `Milestone 2` (containing the rmd, md files for milestone 2, as well as the graph images for milestone 2), and `output` (containing the csv file of a summary table from one of the research questions from milestone 1 and the rds file of the ANOVA model object from milestone 2 task 3).




