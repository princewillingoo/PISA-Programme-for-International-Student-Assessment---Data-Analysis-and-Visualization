# Project: PISA Dataset Analysis - International Education Analysis
## Conducted by: Princewill Victor Inyang

## Introduction

**PISA** - Programme for International Student Assessment 2012 study, gathered data about student performance, student life, and school quality from 65 diffrent countries. The data is broad in areas of features, insight, depth and amount.

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It focuses on examining how well prepared the students are for life beyond school. Around 510,000 students in 65 countires took part in the PISA 2012 assessment. Representing about 28 million 15-year-olds globally.

> Here, I'd be exploring and analyzing the dataset from the PISA program which is an international assessment program of educational methods and schooling systems across different countries. Particularly, this data, which I will be analyzing, contian the assessments of performance of students in Math, Science, and Reading.

## AIM
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

- In Part I, Exploratory data visualization, I'll use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

- In Part II, Explanatory data visualization, I'll produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in my dataset. The primary method of conveying my findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.


## Dataset

The data contains 485490 observations with 635 features. The features are a variety of formats: nominal and ordinal categorical, discrete and continuous quantitative, and plain text. The values are simplified and standard scores calculated around OECD (Organisation for Economic Co-operation and Development) feature.

### Main feature(s) of interest in the dataset?

* School/teacher characteristics
* Student Demographics
* Family Demographics


### What features to help support my investigation  and interest?

The summary features in the data set combine similar measures of student information into a single quantitative or categorical value. This allows for direct comparison and contrast. Below are the features:
* 'Country',
* 'Birth_Month',
* 'Birth Year',
* 'Gender',
* 'Mother_Schooling',
* 'Mother_Job',
* 'Father_Schooling',
* 'Father_Job',
* 'Birth_Country',
* 'No_Cellphones',
* 'No_TVs',
* 'No_Computers',
* 'No_Books',
* 'Homework_Study_Time',
* 'Class_Size',
* 'Teacher_Sets_Goals',
* 'Teacher_Encourages_Thinking',
* 'Teacher_Gives_Feedback',
* 'Immigration_Status',
* 'Teacher Student Relations',
* 'Teacher Behavior',
* 'Birth Country of Father',
* 'Birth Country of Mother',
* 'Birth Country',
* 'Wealth',
* 'Experience with Applied Math in School',
* 'Experience with Pure Math in School',
* 'Average Math Score',
* 'Average Reading Score',
* 'Average Science Score',
* 'Max Math Score',
* 'Max Reading Score',
* 'Max Science Score'

## Summary of Findings

- Students with three or more cellphones spend more time studying resulting in higher math scores the reverse is the case with students with lesser cellphones.
- Parents with higher educational level tends to be more wealthy which in turn shows student performing better at math. This dosen't actually meant that student from wealthy familes with educated parents are always going to perform better at math
- Plot shows, more phones, more books and more students move together
- it's obvious that both parents job levels and education level plays a huge role on students performance
- The Diffrent subjects are highly(positive) correlated, with a normal distribution, The rest of the scatter plots don't show correlations. 
- The homework study time and the class size are both skewed to the right, and the maths, reading and science scores have uniform distribution.
- The higher the number of books a student have, the higher the chances of them scoring high in a reading test


## Key Insights for Presentation

We could infer how students perform in diffrent subject based on thier parent job type, parent educuation level, access to electronic gadgets, books, time spent studying after school, relation with teachers and countries of orgin. we measured students performance based on three average scores of math, reading, and science. Also, looked at the teacher behavior distribution through the countries. Finally, we tried to find relation between average math score and wealth based on parent education level.
