# The Doodling Yogi

## Code Institute - User Centric Frontend Development Milestone Project 

[nocheerleader.github.io/the-doodling-yogi-v1-0/](https://nocheerleader.github.io/the-doodling-yogi-v1-0/)

This website was commissioned by Trea Ivory. Trea is a yoga teacher who combines her professional yoga training with her love for illustration. She wanted a website which demonstrated her yoga qualifications, showcased her art work and provided current and prospective students with her contact details and how to connect with her on social media. 

The website highlights the studies undertaken by Trea to become a professional yoga teacher and it displays details of how to contact Trea to obtain a quote for personalised illustration pieces. There is also a section included for Trea’s guided meditation audio files. This was included for her current students so they can follow along at home. 

## UX
The objective when building this website was to provide value to both current and prospective students. After meeting with the client, I knew what she wanted to achieve. She required a website which displayed her studies and professional qualifications, a place where students could connect with her and find her across different social media platforms and a place where she could add value for her students, by giving them access to her guided meditations and her easy to follow illustrated guides. 

I was able to achieve these goals by building a static single page scrolling website divided into clear sections: 

* An About Me section detailing the clients achievements and qualifications which would help to attract new students 
* A Social Media section allowing students to connect with the client and to find out when and where she holds her classes and workshops 
* An Illustrated Guide section for students to use outside of class and to also display the type of illustration commissions the client takes on 
* A Meditation section including audio files to showcase what you’ll participate in if you attend one of the clients classes, or to use independently at home 
* A Contact Form at the bottom of the website to prompt current or prospective students to contact the client with any questions they have after they have visited her website 

## User Stories 
After careful research and brainstorming with the client I knew I wanted to build this website with prospective users in mind. From their perspective I created the following user stories to keep me on track: 

* As a current student, I want to be able to contact my yoga teacher so that I can find out what time the class is on this weekend.
* As a prospective student, I want to review the teachers qualifications, to ensure I am attending classes with a professional. 
* As the husband of a yoga student, I want to review the art work of the teacher, so I can commission a piece for my wife's birthday. 
* As a student, I want access to audio files of guided meditations, so I can practice at home after class.
* As a beginner looking into starting yoga, I want to be able to get a feel for the teacher on her social media, so I can make the best decision before signing up for a new class.

## Wireframes
* The desktop wireframe can be viewed [here](https://photos.app.goo.gl/3Gey3JW2MDYTLmrXA)
* The mobile wireframe can be viewed [here](https://photos.app.goo.gl/6JqkzLfjkSavuoAC7)

## Features
The Doodling Yogi is mobile-first and responsive so users will have a good experience viewing the website at home on their widescreen monitors or while out and about on their mobile screens. 

On the top right of the website there is a navigation menu. When hovered over, the links on the navigation change from white to orange. This allows the user to identify these elements as links. The navigation bar allows users to quickly navigate to any section of the website they require by clicking on the relevant link. This menu is always available when scrolling through the website. On mobile devices this becomes a hamburger navigation menu to fit on the smaller screen. 

The logo placed on the top left on the screen works like a homepage button, wherever you are on the website clicking the logo link will return you to the top of the page. Like the links mentioned above, the logo changes color when the user hovers their mouse cursor over the top. 

The social media icons act as links to relevant social media platforms. When hovered over they change color to identify them as a link. These links allow users to reach the social media profile of the yoga teacher, including Instagram, Facebook and Twitter. Through these links the user can find more relevant information about the yoga teacher and her classes. 

The contact from allows users to get in touch with the yoga teacher, users can leave submit their email address and questions or messages from the teacher and she can reply via email at her convenience. 

## Features Left to Implement
In the future, I would like to add additional features for the client including: 

* A class schedule and a map to the class location 
* The functionality to check availability and book classes online
* An e-commerce section to allow the client to sell her illustrated products online  
* A blog with fresh content added regularly by the client to keep students returning to her website for up to date information  

## Technologies Used

* **CLOUD9 IDE**
https://c9.io
Cloud9 is an online integrated development environment that supports multiple programming languages HTML, JavaScript and Python. I used it to build and save my project and also to push my commits to GitHub as it has a built in Unix terminal. 

* **HTML5**
https://www.w3.org/html/
HTML5 is the 5th edition of the internet's core markup language used for creating content for the web and web applications. I used this as the foundation to build the structure of the website. 

* **CSS** 
https://www.w3.org/Style/CSS/Overview.en.html
CSS aka Cascading Style Sheets is a file used to keep the structure of a document (HTML) separate from the details of how to design and display it. I keep my style.css file separate from my index.html to make maintenance of the website less complicated. 
 
* **BOOTSTRAP 4.0.0**
https://getbootstrap.com/
Bootstrap is an open source CSS framework library used to build mobile-first responsive websites and web applications. The head of my HTML file contains a link to the version 4.0.0 of Bootstrap, the latest version available at the time of deployment. I used Bootstrap for speed of build and because it allowed customisation to fit my design style. 

* **JAVASCRIPT and JQUERY**
https://developer.mozilla.org/en-US/docs/Web/JavaScript
https://jquery.com/
JavaScript is an object-oriented computer programming language that follows the ECMAScript standards. While JQuery is an open source JavaScript library used to simplify HTML and DOM manipulation . As the scope of this project required a static website I have only included JavaScript and JQuery in the technology used section as they are required for the Bootstrap framework to function correctly. You will find source links to their CDNs at the bottom of my index.html file. 

* **FONT AWESOME**
https://fontawesome.com/
Font Awesome is an open source toolkit used to add fonts and icons to a website. I used icons from the library by adding a link to the Font Awesome CDN in the head of my index.html file. I used icons to display the links to the clients social media sites as they added a visual meaning to the elements. 

* **GOOGLE FONTS**
https://fonts.google.com/
Google Fonts is an API which allows developers to use web fonts in their sites and web applications. From the Google Fonts collection I chose two fonts for this website - Pacifico and Ubuntu. After making my selection I added a stylesheet link to request the desired web font from the API and finally in the style.css stylesheet I styled an element with the requested web font.

## Testing

Firstly I checked index.html on [validator.w3.org/](https://validator.w3.org/) and removed fixed the errors and warnings identified. I followed this up by checking style.ccs on [jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/) where no errors were found besides known issues with Bootstrap validation. An explanation of why these errors exist is found on the official Bootstrap website: [getbootstrap.com/docs/4.0](https://getbootstrap.com/docs/4.0/getting-started/browsers-devices/#validators)

To check responsiveness I viewed the site on a few different devices of family and friends, including: 
- Mac 21” monitor 
- Windows 15” monitor 
- iPhone 7 Plus 
- iPhone 8 Huawei P21 
- Samsung Galaxy S5
- iPad Mini 
- iPad 768 x 1024

I also used [responsivedesignchecker.com/](https://responsivedesignchecker.com/) and Chrome Dev Tools for testing all other devices.

The site was also tested across multiple browsers to ensure compatibility (Chrome, Firefox, Edge, Safari and Internet Explorer).

When viewed on smaller mobile devices the media queries work as expected. The navigation also collapses into a hamburger drop-down menu as desired, to fit the smaller screen size more efficiently. 

All links change colour when hovered over. And The Doodling Yogi logo acts as a homepage button as expected. 

Testing of the contact form found that the validation of the email address is working correctly. For example, if a user fills in the ‘Email’ field without an @ symbol and clicks the submit button, they will receive a warning that there must be a valid email address including the @ symbol before the form can be submitted. 

I also carried out some testing based on the User Stories created above: 
* As a current student, I want to be able to contact my yoga teacher so that I can find out what time the class is on this weekend.
Testing of the contact form found that the validation of the email address is working correctly. For example, if a user fills in the ‘Email’ field without an @ symbol and clicks the submit button, they will receive a warning that there must be a valid email address including the @ symbol before the form can be submitted. 

* As a prospective student, I want to review the teachers qualifications, to ensure I am attending classes with a professional. 
While on the site I scrolled to the About Me section where I easily found the content required. From here I found links, easily identified by the orange colour and when hovered over an underline appears underneath to acknowledge these are links to the user. The links take the user to the institutes where the client studied to become a professional yoga teacher. 

* As the husband of a yoga student, I want to review the art work of the teacher, so I can commission a piece for my wife's birthday. 
* As a beginner looking into starting yoga, I want to be able to get a feel for the teacher on her social media, so I can make the best decision before signing up for a new class.
This information can be found in the Connect With section. As per the user story above, links in this section are easily identifiable by their orange colour and underline when hovered over. Also, icons of the same orange colour are used as links to the clients external social media platforms where users can find further info about her illustration work and look at things like her class set-ups and her Facebook Group which gives current up to date info to users. 

* As a student, I want access to audio files of guided meditations, so I can practice at home after class.
Scrolling to the Meditation section, I added and tested an audio file. The audio file is an original made by the client. I used the <audio> element to embed this content into the website. And added the controls attribute to allow users to play and pause the audio file, as well as adding the functionality of volume control. There is also some standard text added between the audio tags which will only be displayed in browsers that do not support the <audio> element.

## Deployment

At the start of the build a new repository was created in GitHub and initialised in Git. Throughout the development, the project was regularly pushed to GitHub, ensuring each new piece of functionality would be in a separate commit. 

[nocheerleader.github.io/the-doodling-yogi-v1-0/](https://nocheerleader.github.io/the-doodling-yogi-v1-0/) is hosted using GitHub pages, deployed directly from the master branch.

To run the project locally you can clone this repository directly into any HTML editor, for example ATOM, Notepad++ or Sublime. 

## Credits
---

**Content**
All content in the About Me section, all illustrations and the guided meditation audio file was provided by the client, Trea Ivory. Content for the Meditation section was borrowed from [purposefairy.com](https://www.purposefairy.com/) personal development blog.

**Media**
The illustrations and audio file were both also provided by the client, Trea Ivory. The background image used on the jumbotron came from www.pexels.com



