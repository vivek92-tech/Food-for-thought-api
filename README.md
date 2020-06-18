# Food-For-Thought-API

Food for thought source code

# Features:

 * Registering and logging to user account.
 * posting and listing content feeds.
 * Image Uploading.
 * Tags and Ingredient type filtering
 * Test driven development

# Technology Stack:

 * Python
 * Django and Django REST Framework
 * PostgreSQL
 * Docker
 * Travis-CI
 * Linux development environment
 
### Run the server
 $docker-compose up
### Setup Database
$docker-compose build
### Make Migration for core app
$docker-compose run app sh -c "python manage.py makemigrations core"
### For testing
$docker-compose run app sh -c "python manage.py test && flake8"
