# World-Development-Statistics
# Deliverables
All of your projects will comprise of a written technical report and a presentation. As we continue in the course, your technical report will grow in complexity, but for this project it will comprise:

A Jupyter notebook that describes your data with visualizations & statistical analysis.
A README markdown file the provides an introduction to and overview of your project.
Your presentation slideshow rendered as a .pdf file. NOTE: Your entire GitHub repository will be evaluated as your technical report. Make sure that your files and directories are named appropriately, that all necessary files are included, and that no unnecessary or incomplete files are included.
For your presentation, you'll be presenting to a non-technical audience. You should prepare a slideshow with appropriately scaled visuals to complement a compelling narrative. Presentations should be about 5 minutes. Time tends to fly when presenting, and doing a dry run for a friend or family member is a great way to practice.

# Problem Statement
You will be asked to come up with a data science problem. For this project, your problem statement is up to you! Below are some guidelines/things to consider when crafting a problem statement:

Consider your audience. Who is your project going to help? Who will your presentation be geared towards? Establishing your audience first can help you narrow down your scope.
Consider the data you will use. Based on the contents of this data, think about some questions you could reasonably answer. These questions should aim to solve some kind of problem.
Based on these questions, what would bring some kind value to your audience? This can be business insights, increase sales, make decisions, etc.
Put everything from the above steps together into a few sentences that describe the specific problem you are trying to solve and who it will benefit.
Here are some example prompts if you need inspiration:

Climate change will disproportionately affect countries at lower sea levels. In anctipation of sea level rise, you have been hired by a non-profit to identify which countries are most at risk and to report back the top 5 countries where relief and aid should be directed*.
You work for a global shipping company. Your higher ups have asked you to identify which countries (and mores specifically which cities) are the best candidates for expansion of port facilities. Your company is interested in countries that are developing quickly, as these ones will soon demand more goods imported via your company's shipping fleet.
Feel free to be creative with your own prompt!


# Our Topic 
There are 3 data sets included in the data folder for this project. You are required to pick at least two of these to complete your analysis. Feel free to use more than two if you would like, or add other relevant datasets you find online.
We're going to take a look at World Development Statistics from Gapminder, an independent Swedish foundation that aims to make data about the world more accessible and reliable. A good introduction on Gapminder is this Ted Talk from Hans Rosling, which also shows how effective data visualization can be for your audience.
Hint: The Gapminder website has way more datasets
https://www.gapminder.org/about/
https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen

# Technical Report Template
Future projects will require you to decide on the entire structure of your technical report. Here, we provide you with a simple EDA template in a Jupyter notebook that will help to guide your data exploration and analysis. If you choose to edit the core structure of this notebook, make sure you don't exclude any of the requested operations.

# Project Overview Guidelines

This is intended to provide a high-level guideline that can be applied to all projects, with the goal of creating portfolio-ready repos that you will be proud to share with recruiters and future employers.

There should be a clear flow from one notebook to the next. The entire project tells the story. Viewers of your project shouldn’t have to search through notebook after notebook looking for specific parts. It should be very clear from markdown, code comments, executive summary. 

We like to see how you think and work, but that is why we have labs! Projects repositories should be well polished and have a logical flow. This means that projects should be:
- Well organized
- Easy to follow (commenting and markdown really helps here!)
- Replicable (relative file paths and error-free)


## File structure

- README.md. This should include:
  - Problem Statement (1-2 sentences)
  - Executive Summary (2-3 paragraphs)
    - This section should include a brief overview of your process, models used, important findings and/or metrics, model performance, etc.      and a brief summary of conclusions and recommendations.
  - File Directory/table of contents
    - Files should be clearly labeled with descriptive names
  - Data  and Data Dictionary
    - Write a sentence or two about the source of your data. If you are not including your data in the repo share a link to your data source.
    - Include all features in your final cleaned csv/file
    - Include engineered features
  - Conclusions and Recommendations
  - Areas for Further Research/Study
  - Sources
  - Any important visualizations - these can be included in the Executive Summary or Conclusions/Recommendations, or as its own section. Use good judgement! Include a few here that really highlight your findings.
- Data folder
  - Original data
  - Cleaned data
- Code folder
  - 01_Data_Collection 
  - 02_Data_Cleaning
  - 03_EDA
  - 04_Modeling _(__Note:__ This is not applicable to this project, but it will be for future projects.)_
    - This can be multiple notebooks - for example…
    - 04a_Logistic_Regression_Models
    - 04b_Naive_Bayes_Models
- Presentation folder
  - Presentation pdf
  - Can include images folder if needed
- Scratch folder
  - This can include any of your work that you want to save, but do not want to be evaluated on.


## Notebook cleanup! Before you submit….
- Remove any erroneous libraries from imports - only import the libraries you need for this specific notebook
- Remove any erroneous cells. Did you create a function that you don’t use? Remove it! Did you create a bunch of visualizations and realize that there is viz in there that doesn’t add to your data storytelling? Remove it! 
- It is good practice to restart your kernel and run all cells before submitting. This is also a great way to double check for errors and remove those.
- Data Science is recursive. There's a good chance that you will get through your EDA, start modeling, and then go back to realize there are more features that you want to explore. That's great! But try to keep your notebooks siloed. You can always revisit a notebook to add in more work, but all EDA should be in the EDA notebook, all modeling should be in the modeling notebook, etc. The idea is to capture the workflow, rather than your flow of thought.

Remember, these are guidelines! Your structure will change from project to project, but this is a great baseline format to follow. Now let's get to work on some portfolio-worthy projects!


