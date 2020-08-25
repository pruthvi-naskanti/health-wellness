# Walk Tracker
WalkTracker is a digital health and wellness platform that provides services such as calorie tracking, one-on-one nutrition and fitness coaching, and diet and workout plans. Developed for both Android and iOS platforms, the app takes a holistic lifestyle tracking approach to keep users engaged and motivated.

## Link to Hosted Page
[Click here](https://raviteja444.github.io/health-wellness/)

## Link to Repository
[Click_here](https://github.com/RaviTeja444/health-wellness)

## Statement of purpose
WalkTracker is a free to download and use mobile application which provides a health promotional service assisting users to track their health and wellness progress. We plan to develop a software that helps to see better results in weight loss, building muscles, toning up, or controlling medical conditions. Premium plans along with personal coaching with fun health group and wellness challenges, while also being able to share results.

## Objective
Having a fit and healthy body is everyone's dream, but it has somehow not been everyone's cup of tea. Between 2017 and 2018, the National Health and Nutrition Examination Survey observes 1 out of every 4 children are suffering from Obesity, also obesity is linked to more than 60 chronic diseases and there is epidemic of obesity around the world.

In the U.S, childhood obesity alone is estimated to cost $14 billion annually in direct health expenses. Unhealthy lifestyle and eating habits has direct impact on physical health causing damage to metabolism, which has impact on mental well-being too. Most part of the problem comes from a lack of awareness of what people are eating and how much energy they burn every day.

WalkTracker is a digital technology to help people eat better, get fitter and lose weight. The primary solution is delivered via a smartphone app (iOS, Android) with a team of qualified diet/ fitness expert’s available in-app. It also allows optional integration with various tracking wearables. The funds would be used in developing AI and ML interface, so that it can service more users with fitness suggestions, healthy alternative food and task recommendations.

Our app will help users to track their health and wellness progress using step count. Also, will be providing points based on the steps count. The rewarded points can be used to buy products like Our University T-Shirts,Caps.

## Benefits
1. The app helps users to track their steps, food intake and other health measurements which helps to track their health.
2. Users who gained points which can be used to buy products in our App market.
3. The user statistical data can be used to predict users health prior to attack.


## Schedule


## Budget
The project budget includes labor costs, material acquisition and operating costs.


Link to cost estimation: [Cost Estimation](https://github.com/RaviTeja444/health-wellness/blob/master/CostEstimate.xlsx)


![](https://github.com/RaviTeja444/health-wellness/commit/a1b5c24b417b051df3d693a130ef3de9057c2a3c)


## Roles
| Client  | Dr. Rhonda Beemer  |
|---|---|
| Project Manager  | Ravi Teja Pagidoju  |
| DB Administrator | Gopichand Bhandarupalli |
| Team Lead | Sowjanya Janapatla |
| Full stack Developer | Bhanu Prakash Thota |
| Full Stack Developer | Navya Devineni |
| Full Stack Developer | Sindhu Rani |   


## Evaluation


## JIRA LINK to PROJECT :
[JIRA Link](https://health-wellness.atlassian.net/secure/RapidBoard.jspa?rapidView=1&view=planning.nodetail&selectedIssue=HEAL-3&issueLimit=100)

## Epics / User Stories / Tasks 
[EPIC Link](https://health-wellness.atlassian.net/browse/HEAL-2).
We have one epic and one user story under the epic.Below is the link for Epic.

## Sprint 1(Active)
![](https://github.com/RaviTeja444/health-wellness/blob/master/Sprint1.PNG?raw=true)

## Sprint 2(Future)
![](https://github.com/RaviTeja444/health-wellness/blob/master/Sprint2.PNG?raw=true)

## Entity Relationship Diagram
![ERD](https://github.com/RaviTeja444/health-wellness/blob/master/GDP1.png?raw=true)

## RELATIONS:

USER(UserId,EMAIL,USER_NAME,USER_ROLE,PASSWORD,DATE CREATED,DATE_LAST_ACCESSED,HEIGHT,WEIGHT,IS DIABETES,AGE,GENER)
GROUP (GroupId,UserId, NAME, CREATOR, DATE_CREATED, DATE_LAST_EDITED)
FK UserId USER

## Business Rules for the ER Diagram:

A certain HEALTH WELLNEESS is interested in storing information about 
USER,DAILYLEVEL,USER_POINTS,CHALLENGE_NAME,GROUP_MEMBER,GROUP AND TARGET.

For each USER,The HEALTH WELLNESS would like to store a Unique UserId, EMAIL,USER_NAME,USER_ROLE,PASSWORD,DATE CREATED,DATE_LAST_ACCESSED,HEIGHT,WEIGHT,IS DIABETES,AGE,GENER.

For each GROUP,The Health wellness would like to store a Group unique Id,name,Creator and Date_Created,Date_Last_EDited.

FOR each Group_Member, The Health wellness  would like to store DATE_INVITED,DATE_ACCEPTED_INVITE,DATE_REJECTED_INVITE,DATE_LEFT_GROUP.

FOR each DAILYLEVEL, The HEALTH WELLNES would like to store UserId,step count, Hydration_level,Sleep_hours,Fruits_consumed,Calories_consumed,OTHERS,Date_of_measurement

FOR each USER_POINTS, The HEALTH WELLNESS would like to store USER POINTS.

FOR each TARGET, The Health wellness would like to store TARGET_NAME,TARGET_DESCRIPTION AND TARGET_NUMERICAL_GOAL.

FOR each CHALLENGE_NAME, The HEALTH WELLNESS would like to store CHALLENGE_NAME,designer,date_created,date_last_accessed.

## Link to Sample Input Data for Database
[Sample Data File](https://github.com/RaviTeja444/health-wellness/blob/master/GDP_Sample_Input_data.xlsx)

## Link to approximate schedule
![Schedule Management](https://github.com/navyadevineni/health/blob/master/Screenshot%20(1).png?raw=true)

## Technology Stack
* Nodejs : Its an open source cross platform javascript runtime environment that executes javascript code without browser.

* HTML : Its an standard markup language used to design pages to display in broswer.

* CSS : Cascading styling sheets helps to style HTML Elements.

* Javascript : Javascript is a programming language gets executed in browser.

* Heroku : Cloud hosting platform to host our PWA in free tier.

* Github : Cloud Repository Platform used to store code
  
## APP_UX Design
[APP LINK](https://www.figma.com/proto/JuWZstQl4XFCJESZAaNcau/Untitled?node-id=1%3A2&scaling=scale-down)

## Login Page
![](https://github.com/RaviTeja444/health-wellness/blob/master/Loginpage.png?raw=true)

## Forgot Page
![](https://github.com/RaviTeja444/health-wellness/blob/master/Forgotpasswordpage.png?raw=true)

## Create Account Page
![](https://github.com/RaviTeja444/health-wellness/blob/master/create%20account%20page.png?raw=true)

## Step Count
![](https://github.com/RaviTeja444/health-wellness/blob/master/Step%20count%20page.png?raw=true)

## Excercise
![](https://github.com/RaviTeja444/health-wellness/blob/master/Excercise%20page.png?raw=true)

## Points Page
![](https://github.com/RaviTeja444/health-wellness/blob/master/points%20page.png?raw=true)

## Market
![](https://github.com/RaviTeja444/health-wellness/blob/master/market%20page.png?raw=true)

## Group Challenge
![](https://github.com/RaviTeja444/health-wellness/blob/master/challenge%20page.png?raw=true)

## Profile Settings
![](https://github.com/RaviTeja444/health-wellness/blob/master/profile%20settings.png?raw=true)

## Risk & Mitigation
* As we are maintaining health data,we plan for safe and secure database to avoid risk of data loss.
* We maintain high secure Authentication for the users to avoid risk of hacking.

## References
[Google](https://www.google.com/)

   



