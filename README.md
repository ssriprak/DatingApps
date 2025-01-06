# Analysis of Dating App Reviews and Sentiment Classification

Project Overview

This project focuses on analyzing user reviews from three major dating apps: Hinge, Tinder, and Bumble. The objective was to uncover trends, classify user sentiments, and provide actionable insights to improve app performance and user satisfaction. A Tableau dashboard was also developed to visualize key metrics and findings.

## Files in the Project
Dating App Reviews Cleaning - 1.ipynb
Purpose: Data cleaning and preprocessing.
Key Tasks:
	Imported the dataset containing 10,000+ user reviews
 
	Handled missing data (20% of records) and removed duplicates for a clean dataset.
 
	Renamed columns and standardized formats to prepare the data for analysis.
 
	Performed initial exploratory analysis to identify data trends.
 
Running Models on Reviews.ipynb
Purpose: Sentiment classification and visualization.
Key Tasks:
	Conducted exploratory data analysis (EDA) to analyze user ratings and review distributions.
	Built a machine learning model for sentiment classification with 75% accuracy, categorizing reviews as positive, negative, or neutral.
	Developed visualizations such as bar charts and heatmaps to highlight rating trends and sentiment distributions.
	Created a Tableau dashboard for actionable insights.

## Project Deliverables
Data Cleaning: Processed raw data to create a refined dataset, resolving missing values and ensuring accuracy.
Sentiment Analysis: Implemented a machine learning model to classify user sentiments, with an accuracy rate of 75%.
EDA & Insights: Identified that 60% of reviews rated apps 4+ stars, with Bumble achieving the highest average rating.
Tableau Dashboard: Built an interactive dashboard featuring 5+ KPIs such as average ratings, sentiment distributions, and app popularity, empowering stakeholders to improve services.

## How to Use the Notebooks
Prerequisites:
	Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, warnings.
	Tableau for visualizing insights from the dataset.
	A dataset named DatingAppReviewsDataset.csv in the same directory as the notebooks.
Steps:
	Open and run Dating App Reviews Cleaning - 1.ipynb to preprocess and clean the dataset.
	Run Running Models on Reviews.ipynb to perform EDA, sentiment classification, and generate visualizations.
	Use the processed data to create or update the Tableau dashboard for interactive exploration.
