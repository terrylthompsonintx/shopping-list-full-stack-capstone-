# Shopping List Full Stack Capstone
The purpose of this app is to create a menu and a shopping list for a week.

# MVP workflow
* Intro screen.
* --> Explains app
* ----> Click to continue.
* ------> Search screen, user searches for recipe.
* --------> Select a recipe
* --------> Search again or quit.
* ----------> Assign recipe to day.
* Screen displays aggregate shopping list.
* --> User can remove items that they already have.
* ----> Click to continue.
* ------> Final shopping list.
* --------> User can delete items as they add to their basket.
* ----------> Displays page with links to recipes.  User can delete list.

# User Stories
* As a user I want to quickly understand the purpose of the site in order to use it to create a shopping list.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
* As a user I want to be able to search for recipes in order to find the ingredients to add to the shoppng list.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
* As a user I want to select a recipe and assign it to a day of the week in order to view the recipe for that day.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
* As a user I want to aggregate ingredients to a shopping list and view as a web page in order create the meal.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
* As a user I want to be able to delete items from the shopping list that I already have so I dont spend unnecassarily.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
* As a user I want to be able to delete the shopping list and menu once I am finished.
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)

## Screenshots
![Landing page screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl01.png)
![Account setup screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl02.png)
![User homepage screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl03.png)
![Achievement timeline screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl04.png)
![Skills word cloud screen shot](https://github.com/Marjona6/not-just-luck-thinkful-full-stack-capstone/blob/master/public/img/njl05.png)

## Working Prototype
Find a working prototype with Node at https://shopping-list-node-capstone.herokuapp.com/ .

## Functionality
* When the user brings up the landing page it explains the pupose of the app.
* The user then enters the app and searches for recipes.  Once they have selected one, they assign it to a day of thw week.

## Technical

#### Front End
* HTML5
* CSS3
* JavaScript
* jQuery

#### Back End
* Node.js with Heroku implementation
* Express.js
* MongoDB on mLab
* Mongoose
* Mocha and Chai

#### Responsive

* The app is responsive and optimized for both desktop and mobile viewing and use

#### Security

* User passwords are encrypted using bcrypt.js.

## API Documentation
API endpoints for the back end include:
* POST to '/users/create' for creating a new user
* POST to '/signin' to sign in an existing user
* POST to '/new/create' to add an achievement to a user's list of accomplishments
* PUT to '/achievement/:id' to update an existing achievement
* GET to '/achievements/:user' to access all of a user's existing achievements
* GET to '/achievement/:id' to access a single achievement by ID
* DELETE to '/achievement/:id' to delete a single achievement by ID

## Development Roadmap
Planned additional features and improvements will allow users to:
* Be presented with motivational quotations that appear at random on their homepage.
* Enter and store compliments they receive from friends, co-workers, bosses, etc. in a "Bank"; and
* Refer back to these compliments (that help them to see that they are qualified and skilled) by viewing the "Bank."
* Change password
