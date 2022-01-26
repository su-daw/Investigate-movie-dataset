# Investigate-TMDB-Movies-dataset

## About
This project is part of Udacity Data Analyst Nano Degree course requirements.

## Goal
The goal of this project is to conduct a complete data analysis on a chosen dataset and to share findings.

## Steps
 - Look at the dataset and brainstorming questions based on the dataset
 - Data Wrangling
 - Expolarity Data Analysis
 - Report Findings

## Tools
- Python
- Jupyter Notebook
## Libraries
- Pandas
- Numpy
- Seaborn
- Matplotlib

## Dataset
The dataset is from kaggle it consists of more than 10,000 records collected from The Movie Database, and 21 columns such as the revenue, budget and runtime of a movie.
## Questions
- Which movie has the highest and least profit?
- Which movie costed the highest and least budget?
- Which movie has the highest and least revenue?
- Which movie has the highest popularity, in what year and which director?
- What is the average movie runtime?
- Which genre has the highest and least occurence?
- Is there's a relationship between profit and year?
- Which director has the highest movie profit?
- compare the production of movies of the first 15 years and last 15 years
## Findings
<strong>Question 1 </strong> Which movie has the highest and least profit? <br>
We can indicate from the below charts that the highest movie profit is Avatar and least movie profit is The Warrior's Way

<img width="476" alt="Screen Shot 1443-06-23 at 5 18 24 AM" src="https://user-images.githubusercontent.com/89170923/151092956-41eda165-4220-45e8-9fcd-1436b7aba7ec.png"> <img width="427" alt="Screen Shot 1443-06-23 at 5 18 34 AM" src="https://user-images.githubusercontent.com/89170923/151092963-b1a5bf75-bb82-47d3-86be-5df567168f91.png">

<strong>Question 2 </strong> Which movie costed the highest budget?<br>
The below charts shows the highest movie budget is The Warrior's Way and least movie profit is Death Wish

<img width="476" alt="Screen Shot 1443-06-23 at 5 23 56 AM" src="https://user-images.githubusercontent.com/89170923/151093474-605bd0d6-e807-4053-8136-5be9eec444a3.png"> <img width="427" alt="Screen Shot 1443-06-23 at 5 24 05 AM" src="https://user-images.githubusercontent.com/89170923/151093483-42d829cf-ef8c-45b6-ae54-89c900627a85.png">

<strong>Question 3 </strong> Which movie costed the highest Revenue?<br>
The below charts shows the highest movie revenue is Avatar and least movie revenue is Kids's Story

<img width="468" alt="Screen Shot 1443-06-23 at 5 28 26 AM" src="https://user-images.githubusercontent.com/89170923/151093884-3cd3af9c-dacf-4b8b-b35b-54ea4fed0e4b.png"> <img width="467" alt="Screen Shot 1443-06-23 at 5 28 33 AM" src="https://user-images.githubusercontent.com/89170923/151093875-b44d8861-8894-4e1b-99e1-7a106b7a5b65.png">

<strong>Question 4 </strong> Which movie has the highest popularity, in what year and which director?<br>
The below tabel shows that director Colin Trevorrow has the highest movie popularity in 2015 with $136,352,881.0 profit

<p align='center'><img width="285" alt="Screen Shot 1443-06-23 at 5 34 37 AM" src="https://user-images.githubusercontent.com/89170923/151094470-058a1dcd-ac9a-4515-8ec0-7d425fd2a0f8.png"></p>

<strong>Question 5 </strong> What is the average movie runtime? <br>
This Chart shows the Dirstibution of movie runtime and it indicate that the avg movie runtime is between 90 to 100 mins
<p align='center'><img width="467" alt="Screen Shot 1443-06-23 at 5 31 34 AM" src="https://user-images.githubusercontent.com/89170923/151094160-b53bad09-6307-4c78-84a8-e087b1c14764.png"></p>


<strong>Question 6 </strong> Which genre has the highest and least occurence? <br>
The below figures indicates that the top frequent movie genre is Drama with 17.7% Occurrence, whereas the least is Tv Movie with less than 1% occurrence

<p align='center'><img width="400" alt="Screen Shot 1443-06-23 at 5 37 47 AM" src="https://user-images.githubusercontent.com/89170923/151094815-5ead5d1b-cce9-4020-97fc-d8baf72aec87.png"></p>
<p align='center'><img width="400" alt="Screen Shot 1443-06-23 at 5 37 57 AM" src="https://user-images.githubusercontent.com/89170923/151094762-2ccd10f9-dbd4-4ed5-8c8a-5286deeeb7fc.png"></p>


<strong>Question 7 </strong> Is there's a relationship between profit and year? <br>
The below chart shows that as we move forward there is a possible chance that the movie profit increases,
this indicates that profit has a positive correlation with year. As years moves profit grows in direct propotion with it.

<p align='center'><img width="460" alt="Screen Shot 1443-06-23 at 5 41 59 AM" src="https://user-images.githubusercontent.com/89170923/151095149-3ec5040f-8492-4111-a8d6-e4d5f560f4fd.png"></p>

<strong>Question 8 </strong> Which director has the highest movie profit? <br>
James Cameron wins tha battle with highest movie profit

<p align='center'>
<img width="407" alt="Screen Shot 1443-06-23 at 5 44 13 AM" src="https://user-images.githubusercontent.com/89170923/151095376-328ca800-522b-49f1-a717-fc851b123127.png">
</p>

<strong>Question 9 </strong> Compare the production of movies of the first 15 years and last 15 years <br>
We can conclude that that last 15 year ranged between 2001 and 2015 the number of movies has increased insanely comparing with the first 15 years from 1960 to 1975
<p align='center'>
<img width="353" alt="Screen Shot 1443-06-23 at 5 45 09 AM" src="https://user-images.githubusercontent.com/89170923/151095601-17f82149-f3c0-4141-9226-7a0408ef6280.png">
<img width="357" alt="Screen Shot 1443-06-23 at 5 45 23 AM" src="https://user-images.githubusercontent.com/89170923/151095607-8680dd24-d4d5-433e-86e1-f3ace630a94c.png">

</p>

## Resources
- https://numpy.org/doc/stable/reference/generated/numpy.around.html
- https://medium.datadriveninvestor.com/data-science-analysis-of-movies-released-in-the-cinema-between-2000-and-2017-b2d9e515d032
- https://towardsdatascience.com/what-is-feature-engineering-importance-tools-and-techniques-for-machine-learning-2080b0269f10#:~:text=Feature%20engineering%20is%20the%20process,be%20used%20in%20supervised%20learning.&text=Feature%20engineering%2C%20in%20simple%20terms,statistical%20or%20machine%20learning%20approaches.


