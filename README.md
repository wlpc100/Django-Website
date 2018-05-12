# Mango - A Proof of Concept (Based around Tango with Django project)

Mango utilizes the Django framework to allow you to create guides, read, and rate them.

# Hows it work

Django utilizes the sqlite database that comes built in with the django package to store any guide information in a SQL entry. The Django Model system is the groundwork for what fields get saved to the tables, in this case, a guide model. URL requests will access specific views based around the URL, and return the appropriate template while accessing the model information from the database.

## Homepage

![Home](https://i.imgur.com/WVfIiwm.png)

## Adding a Guide

![Add](https://i.imgur.com/ozWpO7v.png)

## Reading a guide

![Guide](https://i.imgur.com/MWGYtD6.png)

## List of Guides

![List](https://i.imgur.com/XoxIIN3.jpg)

# Author

William Lee
