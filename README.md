# YelpCamp
View Live: https://yelp-camp.ca/ 


View Live: https://my-campground.herokuapp.com/ (Until November 2022)

YelpCamp is a website where users can review campgrounds. 
The user can write a review, upload images of a campsite, view other reviews and can comment on reviews.

Uses the MERN stack and performs CRUD operations using a REST API, that I built from scratch

![Image 1](https://raw.githubusercontent.com/himanshup/yelp-camp/master/screenshots/image1.png)  
![Image 2](https://raw.githubusercontent.com/himanshup/yelp-camp/master/screenshots/image2.png)  

## Technologies Used

* Front End: HTML, CSS, Bootstrap
* Back End: NodeJS, NPM, ExpressJS, REST, PassportJS, MongoDB

* Passport.js was used to handle authentication.  

* Performs CRUD operations for users, campgrounds and comments, while limiting access to users to only allow authorized users to edit and delete campgrounds and comments

## Features
* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
* Search campground by name or location
* Sort campgrounds by highest rating, most reviewed, lowest price, or highest price

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/himanshup/yelpcamp.git
cd yelpcamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

To get google maps working check [this](https://github.com/nax3t/google-maps-api) out.
