# Table of contents

* [About UH-Clubr](#about-uh-clubr)
* [Developer Guide](#developer-guide)
* [Development history](#development-history)
  * [Milestone 1: Mockup development](#milestone-1-mockup-development)
  * [Milestone 2: Data model development](#milestone-2-data-model-development)
  * [Milestone 3: Connect UI to data model](#milestone-3-connect-ui-to-data-model)
* [About the Members of UH-Clubr](#about-members)

# About UH-Clubr 

UH-Clubr is a Meteor application providing the directory for the organizations at the University of Hawaii at Manoa. The UH-Clubr application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), contact information for officers, and a few select photos. 

You can find the UH-Clubr website [here.](http://uhclubr.meteorapp.com/#/) 

When you come to the site, you are greeted by the following landing page:

![](images/landing1.png)

Anyone can login to UH-Clubr by clicking on the login button. If the user does not have an account, then he or she may sign up to create an account:

![](images/signin.png)

Once logged in, you can create a profile that provides a biographical statement and list of interests, plus links to selected social media sites (GitHub, FaceBook, Instagram).
  
After creating a profile, you will be listed on the public directory page, which then will allow you to take a look at all the independent organizations at UH Manoa:

![](images/clublist.png)

UH-Clubr also provides a filter page, available to those who can login to the system with their UH account. The filter page allows you to display all organizations with a given interest.

Details regarding the development of the application can be found via the Github organization [UH-Clubr](https://github.com/uh-clubr).
 
# Developer Guide

First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of UH-Clubr] or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000). You may sign up for an account on UH-Clubr if you don't have one, or sign in if you do. 

# Development History

## Milestone 1: Mockup development
This milestone started on November 5, 2018 and ended on November 14, 2018.

The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system. To simplify things, the mockup was developed as a Meteor app. This meant that each page was a template and the UI and the backend functionality weren't entirely implemented.

Mockups for the following six pages were implemented during M1:

The user is greeted by the [landing page.](http://uhclubr.meteorapp.com/#/)
<img width="800px" src="images/landing.png"/>

The user can access the [club directory](http://uhclubr.meteorapp.com/#/list) after signing in:
<img width="800px" src="images/clublist.png"/>

If you are logged in as the master admin, you can edit or delete the clubs by the [following link.](http://uhclubr.meteorapp.com/#/admin)
<img width="800px" src="images/adminpage.png"/>
<img width="800px" src="images/editpage.png"/>

You may also [add a new club](http://uhclubr.meteorapp.com/#/add) as the master admin:
<img width="800px" src="images/addpage.png"/>

If you are logged in as the club admin, you can edit the information of the club you are responsible for as shown [here.](http://uhclubr.meteorapp.com/#/clubadminlist)
<img width="800px" src="images/clubadmin.png"/>
<img width="800px" src="images/editpage.png"/>

Milestone 1 was implemented as [UH-Clubr GitHub Milestone M1](https://github.com/uh-clubr/uh-clubr/milestone/1):

![](images/m1.png)


Milestone 1 consisted of seven issues, and progress was managed via the [UH-Clubr GitHub Project M1](https://github.com/uh-clubr/uh-clubr/projects/2):

![](images/projectboard.png)

## Milestone 2: Data model development 
Milestone 2 was implemented as [UH-Clubr GitHub Milestone M2](https://github.com/uh-clubr/uh-clubr/milestone/2)::


Milestone 2 consisted of eight issues, and progress will be managed via the [UH-Clubr GitHub Project M2](https://github.com/uh-clubr/uh-clubr/projects/3):

## Milestone 3: Connect UI to data model
Milestone 3 will be implemented as [UH-Clubr GitHub Milestone M3](https://github.com/uh-clubr/uh-clubr/milestone/3)::


Milestone 3 will consist of __ issues, and progress will be managed via the [UH-Clubr GitHub Project M3](https://github.com/uh-clubr/uh-clubr/projects/4):

# About Members
Andrea Narciso is an ICS student at UH Manoa graduating in May 2019. She is interested in product development, project management, data and business analysis.
  * [Technical Portfolio](https://narcisoa.github.io/)
  * [LinkedIn](https://www.linkedin.com/in/narcisoandrea/)

Sophia Kim is an ICS student at UH Manoa graduating in May 2021. She is interested in machine learning, cyber security, artifical intelligence and entrepreneurship.
  * [Technical Portfolio](https://sophia-kim.github.io/)
  * [LinkedIn](https://www.linkedin.com/in/sophiajhkim/)

Tysen Imai-Toyama is an ICS student at UH Manoa graduating in May 2020. He is interested in Software development, data analysis and cryptology.
  * [Technical Portfolio](https://tysenimaitoyama.github.io/)
  * [LinkedIn](https://www.linkedin.com/in/tysen-imai-toyama-b91a49149/)

Christopher Nishimura is an ICS student at UH Manoa graduating in May 2020. He is interested in web design, software development and video game design.
  * [Technical Portfolio](https://chris-nishimura.github.io/)
  * [LinkedIn](http://www.linkedin.com/in/christopher-nishimura-8a000bb8)
