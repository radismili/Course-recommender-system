# Course-recommender-system
The model successfully recommends new courses based on desired courses.

Dataset link: https://www.kaggle.com/datasets/khusheekapoor/coursera-courses-dataset-2021

About the data: 

Choosing the wrong courses can cost us a lot of time and money, so it is very important to choose the right courses for us. Recommender systems can help us here, which will recommend ideal courses for us based on our interests and future goals.

This dataset was scraped off the publicly available information on the Coursera website in September 2021 and manually entered in the case where the data was improperly scraped. It can be used in Recommender Systems to promote Coursera courses based on the Difficulty Level and the Skills needed.

Key Attributes:

Course Name;
University: The University or Industry Partner that offers the Course;
Difficulty Level: Beginner, Intermediate, Advanced. Also has Missing Values represented by Not Calibrated;
Course Rating: Rating on a 5-point scale with minimum step value 0.1. Missing Values represented by Not Calibrated;
Course URL;
Course Description.

Objectives:
- Main goal is to create a course recommender system. The model successfully recommends new courses based on desired courses. It checks if the course title exists in a list of courses, computes how similar each course is to the given one, and then sorts and returns the top 5 most similar courses.
- The secondary goal is to explore the data, clean it and do a basic EDA analysis.
