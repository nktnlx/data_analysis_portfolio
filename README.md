# Aleksandr Nikitin - Data Analysis Portfolio 

## About

Hi, I'm Alex! I have a technical background and hold a Master of Science (M.S.) degree in Geoscience from Saint Petersburg Mining University, with a major in Seismic Data Processing and Analysis. I have 12 years of experience in the field of geoscience, where I held roles such as Data Processing Engineer, Head of Department, and CTO in a technological startup. After a year of transitioning from geoscience to Data Analysis, I am currently a Data Analyst at a Fintech company, starting from June 2021.      
Achieved the 7th place at the open Data Analyst 2021 competition held by [Career Factory.](https://contest.careerfactory.ru/contest_inside/1618853698875x612895580932538400)    

My article on Habr on matching two open data datasets with help of Machine Learning ---> [ENG](https://ai.plainenglish.io/unlocking-the-potential-of-open-data-how-to-make-it-work-for-you-a01f7ac1f19) | [RUS](https://habr.com/ru/company/tochka/blog/699490/)     

My Data Analytics blog on [Medium](https://medium.com/@nktn.lx)   

My CV in [pdf](https://github.com/nktnlx/data_analysis_portfolio/blob/main/aleksandr_nikitin_data_analyst_cv_eng.pdf) 

<br>
This repository serves to showcase my skills and as a platform to share my projects, and a way to track my progress in Data Analytics and Data Science-related topics.  
<br>
  

## Table of contents
- [About](#about)
- [Portfolio Projects](#portfolio-projects)
	+ [Video Games Sales Analysis](#video-games-sales-analysis)
	+ [A Mobile Game Data Analysis](#a-mobile-game-data-analysis)
	+ [A Landing Page Design Experiment](#a-landing-page-design-experiment)
	+ [Online Advertising Campaign Analysis](#online-advertising-campaign-analysis)
	+ [Airbnb Listings Analytics](#airbnb-listings-analytics)
- [Study Projects](#study-projects)
  	+ [Advanced A/B Testing Course](#advanced-ab-testing-course)
	+ [Algorithms Training 3.0 by Yandex](#algorithms-training-by-yandex)
	+ [Data Structures & Algorithms in Python](#data-structures-and-algorithms-in-python)
	+ [A/B Testing Course by Google](#ab-testing-course-by-google)
	+ [sklearn ML course](#sklearn-ml-course)
	+ [Kaggle 30 Days of ML](#kaggle-30-days-of-ml)
	+ [Data Analysis Course](#data-analyst-specialization)
	+ [Data Analysis Course Tinkoff-MSU](#data-analysis-course-tinkoff-msu)
	+ [Learning SQL](#learning-sql)
	+ [Python Developer Track](#python-developer-track)
	+ [Computer Science Career Path](#computer-science-career-path)
	+ [Google Python Class](#google-python-class)
	+ [Side Projects](#side-projects)
	+ [Tableau Vizzes](#tableau-vizzes)
- [Certificates](#certificates)
- [Contacts](#contacts)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Video Games Sales Analysis
**Code:** [`video_games_sales.ipynb`](https://github.com/nktnlx/data_analysis_portfolio/blob/main/video_games_sales.ipynb)    
**Description:** The dataset contains 16715 records as of 2016. There is a list of video games with sales (by region), year of release, platform, critics and users score. The project includes the following steps: data loading, data cleaning and preprocessing, filling missing values, EDA (exploratory data analysis), analyzing region based user profiles, measuring statistical factors, hypothesis testing.  
**Skills:** data cleaning, data analysis, descriptive statistics, central limit theorem, hypothesis testing, data visualization.  
**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib.  
**Results:** Review of the global and regional video games markets, data-based business recommendations.  

### A Mobile Game Data Analysis
**Code:** [`final_project.ipynb`](https://github.com/nktnlx/data_analysis_course/blob/main/37_final_project/final_project.ipynb)    
**Presentation:** [`my_project_slides.pdf`](https://github.com/nktnlx/data_analysis_course/blob/main/37_final_project/my_project_slides.pdf)   
**Description:** The final project for 5 month Data Analysis Course. Setup: you're employed in a mobile games development company. A Product Manager gives you following tasks: to find and visualize retention, to make a decision based on the A/B test data, to suggest a number of metrics to evaluate the results of the last monthly campaign.   
**Skills:** data cleaning, detecting data anomalies, python coding, data visualization, descriptive statistics, dealing with outliers, A/B tests, Shapiro–Wilk test, Levene's test, data transforms, Mann–Whitney U test, proportions z-test, bootstrapping, defining metrics.    
**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib, Statsmodels Stats, Bootstrap.     
**Results:** python functions to calculate and plot users retention, hypothesis testing, detecting statistically significant result with a recommendation to push tested in-app changes into production, a set of metrics to evaluate success of promotion campaign.  

### A Landing Page Design Experiment
**Code:** [`notebook.ipynb`](https://github.com/nktnlx/side_projects/blob/master/4_career_factory/notebook.ipynb)    
**Presentation:** [`slides.pdf`](https://github.com/nktnlx/side_projects/blob/master/4_career_factory/slides.pdf)    
**Description:** My solution to an open Data Analyst competition held by [Карьерный Цех](https://careerfactory.ru/). The solution took the 7th place in the competition (≈100 solutions were submitted by participants).     
**Skills:** evaluating A/B-test design, data cleaning, data anomalies detection, checking splitting system, calculating conversion rate, calculating bounce rate, log-scale transformations, Shapiro–Wilk test of distribution normality, A/B-tests (proportions z-test, Mann–Whitney rank test), plotting results, making conclusion and giving recommendations for follow-up actions.      
**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib, Statsmodels Stats.   
**Results:** A/B test design analysis, conclusion on rolling the new landing page design to production, recommendations on how to improve. 

### Online Advertising Campaign Analysis
**Code:** [`ya_ad_int_solution.ipynb `](https://github.com/nktnlx/side_projects/blob/master/6_ya_ad_internship/ya_ad_int_solution.ipynb)    
**Presentation:** [`ya_ad_int_slides_upd.pdf`](https://github.com/nktnlx/side_projects/blob/master/6_ya_ad_internship/ya_ad_int_slides_upd.pdf)    
**Description:** My submission to Yandex Advertising Analytics internship program.    
**Skills:** data cleaning, CTR, CPC, CPA and CR calculation, comparing metrics with competitors, visualizing results, drawing conclusions.    
**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib.     
**Results:** the slide deck with online advertising campaign analysis and recommendations on how to improve based on the service category. 

### Airbnb Listings Analytics 
**Tableau Public:** [`dashboard`](https://public.tableau.com/app/profile/nktn.lx/viz/LondonAirbnbListingsAnalyticalDashboardpractice5/Dashboard1)    
**Dashboard canvas:** [`dashboard_canvas.pdf`](https://github.com/nktnlx/data_analysis_course/blob/main/32_airbnb_listings/dashboard_canvas.pdf)   
**Description:** Tableau Public dashboard consisted of: calculated renting property occupation rate; analytical chart to choose the best property by occupation rate, review score and price per night; a ranked table of top listings by calculated potential annual revenue; average price, average occupation rate and a number of unique listings KPIs; filters by neighborhood, occupation rate and a number of reviews per the last twelve month.    
**Skills:** interview with a customer, requirements capture, designing an analytical dashboard, product delivery.    
**Technology:** Tableau.    
**Results:** created an analytical dashboard to support daily activities of a company involved in apartments renting business. 

## Study Projects
In this section I will provide links to my github repositories containing code and jupyter notebooks I created while passing online courses or while just having fun with data and code.

### advanced ab testing course
**Description:** Advanced A/B testing course by [karpov.courses](https://karpov.courses/simulator-ab). 
This self-paced course explores such topics as Basics of Statistics, Hypothesis testing, Experimental design, Design testing, Confidence intervals, Improving test sensitivity, Metric selection, Cuped, Stratification, Multiple testing, Traffic splitting, Analysis of ratio metrics (Linearization and Delta Method) and a Complete A/B testing pipeline. All with an extensive coding practice in Python.
**Repository:** Check the repository having my solutions on Advanced A/B testing course tasks and challenges ---> [go to repo..](https://github.com/nktnlx/ab_testing_advanced_course)  
**Status:** Completed in June 2023 (please, check the certificates section below).  

### algorithms training by yandex
**Description:** Algorithms Training 3.0 by Yandex. [The course official page](https://yandex.ru/yaintern/algorithm-training).  
This 1 month algorithms and data structures coding journey explores such topics as stacks, queues, dynamic programming, graphs, DFS, BFS, etc.  
**Repository:** Check the repository having my notes and solutions on Algorithms Training 3.0 by Yandex based on the course lectures, tasks and materials ---> [go to repo..](https://github.com/nktnlx/algorithms_training/tree/main/algo_trainings_3)  
**Status:** Completed in April 2023 (please, check the certificates section below).  

### data structures and algorithms in python
**Description:** Data Structures & Algorithms in Python on Udacity by Google. [The course official page](https://learn.udacity.com/courses/ud513).  
This 1 month course introduces common data structures and algorithms in Python. It overviews frequently-asked technical interview questions and teaches how to structure your responses.  
**Repository:** Check the repository having my notes and useful links on Data Structures & Algorithms in Python based on the course lectures, tasks and materials ---> [go to repo..](https://github.com/nktnlx/algorithms_by_google_udacity)  
**Status:** Completed in March 2023 (please, check the certificates section below).  

### ab testing course by google
**Description:** A/B Testing Course by Google. [The course official page](https://www.udacity.com/course/ab-testing--ud257?autoenroll=true).  
This 1 month course covers how to choose and characterize metrics to evaluate your experiments, how to design an experiment with enough statistical power, how to analyze the results and draw valid conclusions.  
**Repository:** Check the repository having my notes and useful links on A/B testing based on the course lectures, tasks and materials ---> [go to repo..](https://github.com/nktnlx/ab_testing_by_google_udacity)  
**Status:** Completed in February 2023 (please, check the certificates section below).  

### sklearn ml course
**Description:** Machine Learning in Python with scikit-learn by France Université Numérique. [The course official page](https://www.fun-mooc.fr/en/courses/machine-learning-python-scikit-learn/).  
This 3 month course is an in-depth introduction to predictive modeling with scikit-learn. Step-by-step and didactic lessons introduce the fundamental methodological and software tools of machine learning, and is as such a stepping stone to more advanced challenges in artificial intelligence, text mining, or data science.  
**Repository:** Check the repository having jupyter notebooks with the course lectures and tasks' solutions ---> [go to repo..](https://github.com/nktnlx/sklearn_ml_course)  
**Status:** Completed in May 2022 (please, check the certificates section below).  

### Kaggle 30 Days of ML
**Description:** 30 days of Machine Learning by [Kaggle](https://www.kaggle.com/thirty-days-of-ml). The course rapidly covers the most essential skills needed to get hands dirty with data and quickly learn how to build machine learning models.  
**Repository:** Check the repository having jupyter notebooks with the course tasks' solutions ---> [go to repo..](https://github.com/nktnlx/kaggle_30_Days_of_ML)  
**Status:** Completed in August 2021 (please, check the certificates section below).    

### Data Analyst Specialization
**Description:** This is a 5 month specialization by [karpov.courses](https://karpov.courses/analytics). The specialization includes Python, API, Git, Airflow, SQL, Statistics, A/B testing, Visualization, Product development and Product Analytics modules.  
**Repository:** Check the repository having 37 data analysis mini-projects ---> [go to repo..](https://github.com/nktnlx/data_analysis_course)  
**Status:** Completed in July 2021 (please, check the certificates section below).  

### Data Analysis Course Tinkoff-MSU
**Description:** This is a 3 month course by [Tinkoff Education](https://fintech.tinkoff.ru/study/academy/analysis/). The course was created for Moscow State University Faculty of Mechanics and Mathematics students and includes following topics: Introduction to Data Analysis, SQL, Data Visualization in Python, A/B tests, Data Interpretation, Models, Logistic regression, Mobile Analytics, Random Forest, etc..  
**Repository:** Check the repository having my code and solutions for home-tasks and projects of the course ---> [go to repo..](https://github.com/nktnlx/data_analysis_tinkoff_msu)  
**Status:** Completed in May 2021 (please, check the certificates section below).   

### Learning SQL
**Description:** SQL queries for tasks from [codecademy](https://www.codecademy.com/learn/learn-sql), [sql-ex.ru](https://www.sql-ex.ru/?Lang=1), [stepik](https://stepik.org/course/63054/syllabus), [sql module on Yandex Praktikum](https://praktikum.yandex.ru/data-analyst/), etc.      
**Repository:** Check the repository having 400+ SQL queries ---> [go to repo..](https://github.com/nktnlx/learning_SQL)  
**Status:** Some of the courses are still in progress.  

### Python Developer Track
**Description:** 25 projects, 154 hours, 300 topics python developer track from [JetBrains Academy](https://hyperskill.org/tracks/2)  
**Repository:** Check the repository having 11 completed projects including: Hangman, Tic-Tac-Toe, Rock-Paper-Scissors games; Matrix calculator, own-coded Regex engine, To-Do list, etc. ---> [go to repo..](https://github.com/nktnlx/jetbrains_python_developer)  
**Status:** Completed 11 projects, studied 116 topics from the track to practice my python skills. Will revert back to the track later.  

### Computer Science Career Path
**Description:** 20 weeks Computer Science Career Path from [Codecademy](https://www.codecademy.com/learn/paths/computer-science). The career path includes following topics: command line commands, git, python 3, OOP, linear data structures, complex data structures, asymptotic notation, recursion, sorting algorithms, search algorithms, graph search algorithms.  
**Repository:** Although the career path has been already completed the repository is still under development, having only 9 listed projects including: words statistics calculator, English nouns pluralizer, English verbs conjugation, censor engine, etc. ---> [go to repo..](https://github.com/nktnlx/cs_path_codecademy)  
**Status:** Completed in July 2020 (please, check the certificates section below).  

### Google Python Class
**Description:** This is a free class for people with a little bit of programming experience who want to learn Python by [Google](https://developers.google.com/edu/python). Topics covered: strings, lists, sorting, dicts, files, regular expressions, utilities, urllib.  
**Repository:** Containing 10 cool projects including: mimicking random text generator, baby-names popularity counter (based on data from The Social Security administration US), etc. ---> [go to repo..](https://github.com/nktnlx/google_python_class)  
**Status:** Completed in November 2020.  

### Side Projects
**Description:** Side projects and various code snippets I'm having fun with.  
**Repository:** pull-ups ladder calculator, motivational bad habits tracker, my solutions to coding problems for Tinkoff Fintech Junior / Tinkoff Internship admission tests, applications to internships, [Google Sheets Course by Yandex Praktikum](https://practicum.yandex.ru/excel-for-work/), etc. ---> [go to repo..](https://github.com/nktnlx/side_projects)  
**Status:** ∞  

### Tableau Vizzes
**Description:** My Tableau Public account ---> [go to Tableau..](https://public.tableau.com/profile/nktn.lx#!/)  
**Status:** ∞  

## Certificates
I believe that the best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result:) So here is a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [Advanced A/B Testing Course](https://drive.google.com/file/d/1rGfXuVLWLkxzrPLE-NgHizMN-tpoZibA/view) (Jun 2023) (karpov.courses)
- [Algorithms Training 3.0 by Yandex](https://drive.google.com/file/d/1EQ5p0F_acNAXgnKBhgGhxLl-8W6HlCid/view?usp=sharing) (Apr 2023) (Yandex)
- [Data Structures & Algorithms in Python](https://drive.google.com/file/d/1iRxdsndxcPoww3QvQIpDvq9rl_NcmoPj/view?usp=share_link) (Mar 2023) (Udacity - Google)
- [A/B Testing](https://drive.google.com/file/d/15eC0plclsU2f3WFzQ7_cVvc-mA8M3h1Z/view?usp=share_link) (Feb 2023) (Udacity - Google)
- [Teamlead 101](https://drive.google.com/file/d/1-12jUVj8OcLlTQ3147syWIP4nf9a2n9P/view?usp=sharing) (Jul 2022) (Stratoplan Management School)
- [sklearn ML course](https://drive.google.com/file/d/1aUNxDbRCgnKkSzq6LPLRY91Of3L_AyR7/view?usp=sharing) (May 2022) (France Université Numérique)
- [Intermediate Machine Learning](https://drive.google.com/file/d/1kqQFRhJtI097SJ7udZVbLRAJBddvWW4S/view?usp=sharing) (Aug 2021) (Kaggle)
- [Intro to Machine Learning](https://drive.google.com/file/d/1cdL1XluCHCKmG0AarthZm74kiem5y33o/view?usp=sharing) (Aug 2021) (Kaggle)
- [Data Analyst Specialization](https://drive.google.com/file/d/16WKsX7z5LpMo1VxpZc7CQsWNzYfUzB6f/view?usp=sharing) (Jul 2021) (karpov.courses)
- [Jira and Confluence basics](https://drive.google.com/file/d/1dTCQGwKoEjBWmeaXHuktiEyYtRvvLPY-/view?usp=sharing) (Jun 2021) (GeekBrains)
- [Databases for Developers: SQL Foundations](https://drive.google.com/file/d/13dHqXw8Ew3r1XfSxPBkT2lF9_1I3M9cu/view?usp=sharing) (Jun 2021) (Oracle)
- [Data Analysis Course Tinkoff-MSU](https://drive.google.com/file/d/15OIzi5H3Kxs4-8gx7FNgMrW1FNdueEKC/view?usp=sharing) (May 2021) (Tinkoff Education)
- [Data Analyst Professional Development Training](https://drive.google.com/file/d/1NqtzP6P5nLn5oSOYNRdq-wZBv6FoheJu/view?usp=sharing) (Mar 2021) (Yandex Praktikum & University 20.35)
- [Data Literacy Certificate](https://drive.google.com/file/d/1zuPfb6Cp3yritjC-fXwOKNXb_FVoHwBp/view?usp=sharing) (Mar 2021) (Qlik Q, accenture, Data Yoga)
- [New Features in Python 3.9 course](https://realpython.com/certificates/4becca93-d978-4e96-8c24-5afe861b3ad2/) (Jan 2021) (RealPython)
- [Fintech Trends](https://drive.google.com/file/d/1L9MISA6nYsf0mJ8c6Mp3davLv-yWKzt7/view?usp=sharing) (Dec 2020) (Tinkoff Education) 
- [Data Science Math Skills](https://coursera.org/share/03d1c12de0037c35bb3dd1e35d23f4d6) (Oct 2020) (Coursera - Duke University)
- [Computer Science Career Path](https://drive.google.com/file/d/1cCcg7Uf4qqGq6B5OFLBPrNAA3ncEYgXD/view?usp=sharing) (Jul 2020) (Codecademy)
- [Learn the Command Line Course](https://drive.google.com/file/d/1yPtPFhvKmsv9rmJbvf3dtarXavpsi6lq/view?usp=sharing) (Jul 2020) (Codecademy)
- [Learn Git Course](https://drive.google.com/file/d/19DrPoYxcjijNvIbnXF959uIO_Kl7TOZ1/view) (Jun 2020) (Codecademy)
- [Learn Python 3 Course](https://drive.google.com/file/d/1VTGmE15-QbwMyscxVpAAKAwllZgc1a8c/view?usp=sharing) (Jun 2020) (Codecademy)
- [English for Career Development](https://coursera.org/share/f7e97252ee37a74d3c1f57f54f5d5a54) (Feb 2018) (Coursera - University of Pennsylvania)
- [Learning How to Learn](https://coursera.org/share/5e7320a42bee969f6e9e6325559e7215) (Feb 2018) (Coursera - University of California San Diego)
- [Fundamentals of Project Planning and Management](https://coursera.org/share/e90fb632268a6c233b6e229c7d068e8f) (Oct 2015) (Coursera - University of Virginia)
- [Introduction to Linux](https://stepik.org/cert/4441) (Dec 2014) (Stepik - Bioinformatics Institute)
- [IELTS Academic](https://drive.google.com/file/d/1bB3bBUtCeHttCQQHdLP6Om45dFgDyXYw/view?usp=sharing) (Overall Band Score 7.0 - Proficient English User (C1)) (Apr 2014)

## Contacts
- LinkedIn: [@nktnlx](https://www.linkedin.com/in/nktnlx)
- Telegram: [@nktnlx](https://t.me/nktnlx)
- Twitter: [@nktn_lx](https://twitter.com/nktn_lx)
- E-mail: nktn.lx@gmail.com
