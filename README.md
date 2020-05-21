# Next-Yogurt-Flavors-to-Launch-Recommendation
Goal:
>The goal of this project is to conduct analytics to help determine what the next yogurt flavors to launch should be.

About the Dataset:  
>I have access to the data from a survey that captures information about consumers' flavor preferences.  
The details of the survey are provided below.  
  
The survey was taken as a non-random sample from the population of customers. The invitation for the survey went to those that had purchased Greek Yogurt in the last 30 days. This screening criteria was calculated based on household, not individual level data. The survey was pre-tested the week prior to the survey being sent out. It was sent out on May 15, 2011. Some surveys were incomplete and some took an unusually long time to complete, which the panel team usually considered a bad sign for the quality of response. Some decided to skip some questions (for Q12, this is identified by all 23 flavors being NA). The survey data are described below. The survey data consist of three tables. One table,survQuestions, contains the survey question text as a single row. The second, survResponses,has the same columns and contains the respondents’ responses. The third, survItemSales,contains all of the relevant item purchases related to the users in the survey.  

1. ID: The UserID for the respondent.
2. V8: Start Date/Time of the response
3. V9: End Date/Time of the response
4. V10: Whether finished the response  
Values: 1= finished, 0=not finished
5. Q1: Have you eaten Greek Yogurt in the past month?  
Radio Button: Yes (1) or No (0). NA means no response.
6. Q2: Of all the yogurt you have eaten in the past month, what percentage was Greek Yogurt?  
Slider: Value between 0 and 100, NA means no response.  
7-14. Q3: What attracts you to Greek Yogurt? (Check all that apply)
Multiselect Checkbox: Value of 1 for each column they checked otherwise blank (NA)  
15-37. Q12: Below is a list of both existing and new flavors. Assume these flavors are all available for your consumption. Please organize the flavors below into how often you would eat each one.  
Each column corresponds to a flavor and contains a 0 (Regularly), 1 (Occasionally), 2 (Never) or NA (did not categorize that flavor or did not complete the question).  
![Image](https://github.com/xinyuxx/Next-Yogurt-Flavors-to-Launch-Recommendation/blob/master/survey1.png)
