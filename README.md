# week13assignment - Devour The Burger app

Github link: https://github.com/sevenspell/burger
Heroku app link: https://lit-everglades-39619.herokuapp.com/

## Description 

This project is to create an app that allows users to indicate what kind of burgers they'd like to order (adding an item to a list) and then choosing to devour it (changing the status of the item) and moving it to a greyed-out list (reflecting the 'devoured' status), with a final option of being able to throw away the wrapper of the burger (deleting the item from the page).

It utilises NPM packages like the express-handlebars, express, and mySql. The app utilises mySql to create a table that stores the data entered by users. It then utilises express for the backend rendering of data, and eventually express-handlebars to capture the data in an html format and then pushing the entire html format to the front-end. It utilises the MVC format, from mysql -> connection.js -> orm.js -> controller.js -> handlebars that also points to the 'public' folder containing the front-end CSS and Javascript files.

## Usage 

1. Go to Heroku app link: https://lit-everglades-39619.herokuapp.com/
https://github.com/sevenspell/burger/blob/master/assets/Screenshot1.png
2. Enter the name of burger you would like to order and click on 'Order this burger'.
https://github.com/sevenspell/burger/blob/master/assets/Screenshot2.png
3. The top left list shows a list of burgers you've entered. Click on 'Devour this!' to eat your selected burger.
https://github.com/sevenspell/burger/blob/master/assets/Screenshot3.png
4. The top right list shows a list of burgers you've devoured. Click on 'Throw wrapper' to throw the wrapper away ie. delete the item from the list.
https://github.com/sevenspell/burger/blob/master/assets/Screenshot4.png
5. The item you've selected to delete will disappear from the page.
https://github.com/sevenspell/burger/blob/master/assets/Screenshot5.png



## Credits
I got a deeper understanding of the MVC model from Wagner (https://wagner-lopes.github.io/).