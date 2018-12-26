# Centro de Fisioterapia

### Overview

Responsive and Semantic six pages website created for a fictional physiotherapy clinic, designed following a mobile first approach built in a grid layout with a main navigation.
* sitemap > https://github.com/pazcm/physiotherapy-centre/blob/master/assets/pre-dev/sitemap.png _(child pages can be added in a future)_
 
The website showcases the treatments, the professionals and the facilities of a physioterapy clinic. It allows the user the navigation through the pages with a main menu, contact with the clinic, consult Pilates classes and follow the centre via social links.

### UX

The aim is to make easier to the user how to get an appointment and provide them with relevant information about the clinic through a minimalist angle/style following _UX Design_ principles, prioritising the usability and accessibility of the site.

##### Assets
- User stories > https://github.com/pazcm/physiotherapy-centre/blob/master/assets/pre-dev/user-stories.png
- Mockups > https://github.com/pazcm/physiotherapy-centre/tree/master/assets/pre-dev/wireframes
- Media > the photos used in this site were obtained from the Web (for study purpose, no for production or comercial uses).

#### Features

- **Navigation Bar** - Allows user to navigate through the site.
- **Pilates Calendar** - Allows users to consult dates/hours for Pilates classes. _(notice: may no content have been added for current month when this project is being reviewed)_
- **Contact Form** - Allows user to send an email to the centre via form.
- **Facilities Gallery** - Allows users to see the facilities provided for the clinic.
- **Social Links** - Allows user to follow the clinic in the social networks. 
- **Mailto Link** - Allows user to send a direct email to the clinic by clicking the clinic email address.

#### Left to implement

- **Click to call** - On devices with phone capabilities, make it easy for users to directly connect with the clinic by simply tapping the phone number. 
- **Direct links** to treatments / location / appointment 
- **Pilates registration** - Form to allow users to register for Pilates classes.

#### Technologies and tools Used
- **IDE Cloud9** (online integrated development environment) used for development with GitHub integration.
- **SublimeText** (proprietary cross-platform source code editor) used for development.
- **Git/GitHub** (web-based hosting service for __Version Control__ using Git) used to manage the code, track the changes of the files and host this project.
- **Balsamiq Web APP** (graphical user interface mockup and website wireframe builder application) used to create the wireframes for the website.
- **HTML5** used to structure and present the content in a consistent and semantic way following the W3C standards.
- **Bootstrap CSS v4.1.3** free and open-source front-end framework used for developing this website taking laverage of the components that contains.
- **Font Awesome icons  v4.7.0** used for getting social icons along the site.
- **Google Fonts** used for the typograhpy of the site.
- **CSS3** used to for giving custom CSS style for the whole site.

#### Testing
Manual testing for compatibility issues and responsive design. All pages of the website were tested continuously during the development. Chrome and Chrome Developer Tools were the main browser and tool used for testing. Moreover, the site was tested using Firefox and Safari browsers.

Each functionality and all modifications were checked in Chrome, Firefox and Safari browsers and tested using developer tools at full width resolution and using several devices emulators with different screen sizes for Responsive testing; such as Nexus 5X, Nexus 10, Galaxy S5, iPhone 6/7/8, iPhone 6/7/8 Plus, iPhone X, iPad and iPad Pro. 

* * *
- HTML was validated using the Markup Validation Service provided by The World Wide Web Consortium: https://validator.w3.org/
- CSS was validated using the CSS Validation Service provided by The World Wide Web Consortium: https://jigsaw.w3.org/css-validator/ 


##### Issues
- Trying to center the Hamburguer Menu for different screen sizes devices (by applying custom CSS and media queries). 
- Making Google calendar responsive (by using bootstrap grid sytem and classes solved the issue).


###### Crossbrower and Responsive test
* * *

|         | Nav Menu | Header Images | Gallery Images | G_Calendar | Contact Form | G_Map | Mailto | Typography | Footer |
|---------| -------- | ------------- | -------------- | -----------| -------------| ------| -------| ---------- | ------ |
| Chrome  | Passed   | Passed	       | Passed	        | Passed	    | Passed	      | Passed| Passed	| Passed	    | Passed	|	
| Firefox | Passed	  | Passed	       | Passed	        | Passed	    | Passed	      | Passed| Passed	| Passed	    | Passed	|
| Safari  | Passed	  | Passed	       | Passed	        | Passed	    | Passed	      | Passed| Passed	| Passed	    | Passed	|
* * *

###### Test case:
- __Contact form:__
1. Go to the "contact" page
2. Try to submit the empty form and verify that an error message about the required fields appears
3. Try to submit the form with an invalid email address and verify that a relevant error message appears
4. Try to submit the form with all inputs valid and verify that a thank you message appears.
* * *




#### Deployment
To put my project up on GitHub and hosted there, I created a repository for it to live in and three branches ('master', 'dev' and 'test').


The project was developed on 'dev' and 'test' branches and the necessary PRs to 'master' branch were created.


Finally under my project settings/GitHub Pages, it was set the Source/master branch and published =>
https://pazcm.github.io/physiotherapy-centre/

#### Credits

###### Issues
The following sites were used as resources to research about issues, get css snippets, debug css and get utilities.

- http://stackoverflow.com/ 
- http://animista.net/play/text
- https://mdbootstrap.com/docs/jquery/navigation/hamburger-menu/
- https://getbootstrap.com/docs/4.1/utilities/embed/
- https://css-tricks.com/
