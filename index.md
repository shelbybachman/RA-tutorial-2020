# RA Tutorial, Fall 2020

## Schedule

### Week 1: Review of R basics

**Readings**
- *R for Data Science*, Sections 1-4

**Tasks**
- Make sure you have the latest versions of [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/) installed
- Complete *R Programming* course in [swirl](https://swirlstats.com/students.html)

### Week 2: Data wrangling & exploration with the tidyverse, part I

**Readings**
- *R for Data Science*, Sections 5-8

**Tasks**
- Complete *Getting & Cleaning Data* course in [swirl](https://swirlstats.com/students.html)
- Develop a list of questions about your dataset (e.g. *R4DS*, Section 7)
- Write an R script which loads your dataset

### Week 3: Data wrangling & exploration with the tidyverse, part II

**Readings**
- *R for Data Science*, Sections 12, 14 & 15

**Tasks**
- Write an R script which transforms your data (i.e. using `filter()`, `select()`, & `mutate()`; *R4DS*, Section 5). For this task, keep the following in mind:
  - Data should be tidy (see *R4DS*, Section 12)
  - Data should be transformed so as to answer the questions you developed last week
- In the script you create, include steps to explore and handle missing values (see *R4DS*, Section 12.5). Key questions to consider for this task are:
  - Are there missing values in your data? Are missing values represented in a consistently, or are there multiple placeholders for missing values? 
  - Can you replace missing values with `NA` in an efficient way?
  - Are there patterns of missingness that you can detect? Might these be meaningful?

### Week 4: Data visualization with ggplot2, part I

**Readings**
- *Data Visualization*, Chapters 1 & 3

**Tasks**
- Complete *Exploratory Data Analysis* course in [swirl](https://swirlstats.com/students.html) (stop at 
"Hierarchical Clustering")
- Develop a list of visualizations you would like to create to illustrate effects of interest in your dataset
- Write an R script which creates relevant summaries of your data, using the `group_by()` and `summarize()` functions (i.e. *R4DS*, Section 5)
- If you have time, try creating a few basic visualizations using `ggplot2`

### Week 5: Data visualization with ggplot2, part II

**Readings**
- *Data Visualization*, Chapters 4, 5 & 8
- *R for Data Science*, Section 28 (review)

**Tasks**
- Apply what you have learned from the readings on `ggplot2` to plots for your dataset to improve aesthetics of your plots and add functionality such as grouping and facets
- Try using `ggplot2` to create different kinds of plots from those which you have made already, using a dataset at [this site](https://github.com/rfordatascience/tidytuesday)

### Week 6: R Markdown for reproducible reporting, part I

**Readings**
- *R for Data Science*, Section 27
- *Reproducible Research with R and RStudio*, Chapters 1, 2, 3 & 10

**Tasks**
- Create an R markdown document (and knitted html report) which organizes and displays all the code and figures you created for your datase

### Week 7: R Markdown for reproducible reporting, part II

**Readings**
- *Reproducible Research with R and RStudio*, Chapter 12
- *R for Data Science*, Section 29

**Tasks**
- Review [this tutorial](https://ourcodingclub.github.io/tutorials/rmarkdown/) to make sure you are comfortable with (a) markdown syntax and (b) R markdown basics
- Finalize your markdown document: apply a (non-default) theme to your R markdown report, be sure that each chunk of code is visible (along with its output), organize your document into logical sections labeled with headers and subheaders, and add (markdown-flavored) text to describe what each chunk of your code does. Be sure that the figures you create are a reasonable size.

### Week 8: Distributions & descriptive statistics

**Readings**
- [This tutorial](https://tinystats.github.io/teacups-giraffes-and-statistics/02_bellCurve.html) on the normal distribution
- [This tutorial](https://tinystats.github.io/teacups-giraffes-and-statistics/03_mean.html) on measures of central tendency
- [This tutorial](https://tinystats.github.io/teacups-giraffes-and-statistics/04_variance.html) on measures of spread

**Tasks**
- Write some R code to apply methods from the readings to visualize and understand distributions in your data, and to compute measures of central tendency and spread
- Incorporate your R code into your R markdown document

### Week 9: Practical

### Week 10: Methods, TBA

### Week 11: Methods, TBA

## Books & Resources

Gandrud, C. (2020). *Reproducible Research with R and RStudio* (3rd edition). Chapman & Hall.

Healy, K. *Data Visualization: A practical introduction*. [https://socviz.co/](https://socviz.co/)

Wickham, H. & Grolemund, G. *R for Data Science*. [https://r4ds.had.co.nz/](https://r4ds.had.co.nz/)

## Demos

[example_script.R](https://drive.google.com/file/d/1aBXjcbxlCJy8HSl7hnBTpQC__XKvrYh8/view?usp=sharing)

## Useful links

[swirl](https://swirlstats.com/students.html): learn R interactively

[mycodingclub](https://ourcodingclub.github.io/tutorials.html): variety of R tutorials

[UCI ML database](http://archive.ics.uci.edu/ml/datasets.php?format=&task=&att=&area=&numAtt=&numIns=&type=&sort=taskDown&view=table): variety of sample datasets
