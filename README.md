# Ruby on Rails Tutorial
http://guides.rubyonrails.org/getting_started.html

## Authentication
If the page asks for a username and password, the username is "sydney" and the password is "yang".

![Screenshot](app_screenshot.png)

## Models
We have an article model, which is comprised of a title and text.


## Controllers
"Receive specific requests for the application."
Take user input and call appropriate methods. 

## Views
Display output (comments, articles).

# Database Operations (CRUD)

## Create
The articles controller takes user input and calls methods to create and save a new article. 
The article model ensures that each article has a title that is at lease five characters in length, and articles will only be saved if they have a valid title.

## Read
The articles controller lists all of our articles with an index method and displays them with a show method.
These are shown to users through views, which contain links to actions in controllers.

## Update
The articles controller contains an edit action, which allows us to modify and save existing articles.

## Destroy
Articles controller can delete articles and then redirect to the index.

## Commenting
Each comment is associated with only one article, but each article can have multiple comments. The comment controller allows us to create and destroy comments.

![Screenshot](comment_screenshot.png)


