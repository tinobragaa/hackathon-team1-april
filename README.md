# NeuroSisters

## Code Institute April 2024 Hackathon
![readme_image](https://github.com/tinobragaa/neuro-sisters/assets/20447596/aebadcd4-14da-4fcb-96c8-2c7f6c339306)

## Live Site

This project was created by **HerHealth Hacktivists** and is deployed and can be accessed at [neuro-sisters](https://neuro-sisters-37c8c20181fb.herokuapp.com/).

## Contents
- [Purpose](#purpose)
- [Objective](#objective)
- [User Experience](#user-experience)
  - [User Stories](#user-stories)
  - [UXD User Experience Design](#uxd-user-experience-design)
  - [Technologies Used](#technologies-used)
  - [Languages](#languages)
- [Testing](#testing)
  - [Code Validation](#code-validation)
- [Deployment](#deployment)
  - [Heroku](#heroku)
  - [Features Left to Implement](#features-left-to-implement)
- [Credits](#credits)
  - [Code](#code)
  - [Acknowledgements](#acknowledgements)
***

## Purpose

The purpose of this project is to work together in a small Agile team, to build a web application relating to Code Institutes Reimmaging Womens Health Hackathon

## Objective
A website where women who are mothers or female carers of  neuro divergent adult children can find out about support and resources for their own mental and physical health.  The site has login functionality and once logged in users can see posts from others regarding suggestions on how to maintain and enhance their mental and physical health.  All users also have a profile page.  This theme was chosen as although there are many support groups and resources for carers of neuro-divergent children, there aren't many groups or resources for carers of neuro divergent adults.


## User Experience

### User stories
1.  As a user I want to be able to login and logout.
2.  As a user I want to be able to add posts about mental and physical wellbeing of female carers of adults who are neuro diverse.
3.  As a user I want to be able to filter posts on mental and physical wellbeing.
4.  As a user I want to be informed about resources available to those who are supporting and caring for neuro diverse adults.


### UXD User Experience Design

#### Colour Scheme

Colour scheme used was based on these templates and were designed to be calm and restorative.
[colour scheme templates](https://colorhunt.co/)

 

## Technologies Used

* [Django]https://www.djangoproject.com/) Python framework for handling REST API calls and creating the site structure.

* [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) CSS Library for styles

### Languages

* [Python](https://www.python.org/) and [Flask](https://flask.palletsprojects.com/) used for the application backend.

* [HTML](https://devdocs.io/html/) stands for HyperText MarkUp Language and is used to put content and structure on a web page.

* [CSS](https://devdocs.io/css/) stands for cascading style sheets and is used to style a webpage.

* [Javascript](https://www.w3schools.com/js/DEFAULT.asp) is used to implement interactivity on the site.

### Database schema

The database for the blogs was created in [Oracle](https://www.pro-dba.com/oracle-services/oracle-support/)

The database schema is below.

![image](https://github.com/tinobragaa/neuro-sisters/assets/20447596/273f41b1-f7e9-48a3-b3b2-3d5578f28e37)


## Testing

All testing was done manually.

## Deployment

Deployment was done successfully using heroku. The deployment process is outlined below. However due to issues with heroku we were unable to use automatic deployment in heroku, meaning the project hasd to be manually deployed from the terminal.

### Heroku

- While having your project open in your IDE, navigate to the terminal
- Enter ```heroku login -i``` and login when prompted
- Run the command ```heroku create your_app_name_here``` to create a new app, replacing ```your_app_name_here``` with the name you want to give your app. This will create a new Heroku app and link it to your repository.
- You can then access the app via the Heroku dashboard and set up your config vars.
- Select "Settings" from the tabs.
- Click "Reveal Config Vars".
- Add the necessary config vars as your project requires.
- Select "Resources" from the tabs.
  1. Select "Heroku Postgres
  1. Choose your desired plan name from the dropdown
  1. Click "Submit Order Form"
  1. Your add on should appear in the list
  1. Now search for "Heroku Redis" and follow steps 2-4.
- To deploy the site, run the command ```git push heroku main```
  - If this fails, you can check whether the Heroku remote is connected by running ```git remote -v``` and it should appear on the list
 - Click `View` on the deployment page of Heroku to view the deployed site.
The site is now live and operational

## Features Left to Implement

We thought about how to improve the app. Some ideas were:
1. To add search functionality for the blog posts.
2. To allow users to add pictures on the site of resources they found useful.
3. To allow users to view the posts they have created in their profiles and to edit these there.

## Credits

1. Picture on home page was created using DALL-E-3.
2. Images on the site came from [unsplash](https://unsplash.com/)
   

### Code

Code was written by different team members and different aspects as shown.
1. Tino got the repo up and deployed the site to heroku. 
2. Collaborators then cloned the repo and set it as remote. Collaborators could then work on their code and issue pull requests when each feature was ready to be merged into the main branch.
3. Collaborators were:
  - [Alex](https://github.com/alexandergrib)
  - [Allina](https://github.com/TeodoraAlina)
  - [Tino](https://github.com/tinobragaa)
  - [Justyna](https://github.com/justynath)
  - [Lauren](https://github.com/Lauren21717)
  - [Debbie](https://github.com/debbiect246)
  - [Amir](https://github.com/AmirAkmed)


