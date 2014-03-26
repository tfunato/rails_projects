rails_projects
==============

Ruby on Rails Projects
-----------------------

**first_app project**
    [Ruby on Rails Tutorial: Learn Web Development with Rails] tutorial application

http://tatsu-zine.com/books/railstutorial

Deploy to heroku first_app
---------------------------

Heroku apps expect the app directory structure at the root of the repository.  but first_app is in a subdirecotry.

So..to fix it,git subtree command.

    git subtree push --prefix first_app heroku master


