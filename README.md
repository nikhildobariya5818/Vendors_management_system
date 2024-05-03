﻿# Vendors_management_system

This repository contains a Django project with a RESTful API using Django REST Framework.

## Prerequisites

- Python (version 3.x recommended)
- Django
- Django REST Framework


## Create a Virtual Environment:
- pip install virtualenv
- virtualenv venv

## Install Dependencies:
- pip install django
- pip install djangorestframework

## Set up a new project with a single application
- django-admin startproject vendor_manegment_system                 
- cd vendor_manegment_system
- django-admin startapp Vendors_app              

## Database migration                    
- python manage.py makemigrations      
- python manage.py migrate


## Running the server
- python manage.py runserver
