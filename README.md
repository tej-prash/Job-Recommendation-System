## Dataset

Dataset to be used is as follows:
https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey#survey_results_public.csv

Dataset for job-postings
https://www.kaggle.com/PromptCloudHQ/us-technology-jobs-on-dicecom

## Feature Extraction and preprocessing

To run the files, download the stack overflow dataset from the given link and place into /data/user_preprocessing folder. The feature extraction and preprocessing of the user profiles are being done by feature_extraction_user_a.ipynb and feature_extraction_user_b.ipynb. The extracted features are already in /data/user_preprocessing folder.


## Collaborative Filtering model

To run the files, download the stack overflow dataset and the job-postings dataset from the given link and place into /data/collaborative filtering folder.
Run collaborative filtering.ipynb to check the output of CF recommendations based on Content based recommendations.

## Content Based Filtering model-
In order to run the content-based filtering model:
1) The following modules need to be installed
spacy
nltk
sklearn
scipy
2) Kindly download the two datasets mentioned above and place them in the data folder with the following names:
Job Postings Dataset-dice_com-job_us_sample.csv 
Stackoverflow Developer Survey 2018-survey_results_public.csv
3) The core code for content based filtering is in Job Postings Preprocessing.ipynb. The Recommendations can be obtained by running the second cell. The entire code is organized in a class called job_postings. 
3) The model depends on all files in the data folder. The csv files in data folder contain the final user and job profiles
4) The csv files contained in the ./data/job_profile and ./data/user_profile contain the independent job and user profiles
5) The recommendations.csv contains top 10 recommendations for a random sample(first 200 users) of the Stack Overflow dataset
7) Cells 3 onwards contain code snippets attempted during the preprocessing stages
NOTE: To get your own recommendations, pass 1 as the third parameter and you will be prompted to enter your details

About Inferences.ipynb
1) This contains code which was used to make inferences about the dataset
