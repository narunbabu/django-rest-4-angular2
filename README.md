# # django-rest-4-angular2 REST Framework

A simple example application where an Angular 2 app talks to an API running
Django REST framework.

## Setup

Install dependencies and run migrations to set up the app:

- Create a virtualenv env with "virtualenv env"
- Run `env\Scripts\activate.bat`
# And run following
## Optional
pip install Django==1.11.2
pip install djangorestframework==3.4.0
pip install django-cors-headers==1.1.0
## or run the following
pip install -r requirements.txt

## And these
cd exampleapp
python manage.py migrate // Creates database
python manage.py loaddata sample-dinosaurs.json // Imports data

## Run the app

Run the REST server:

```
# in the exampleapp folder
python manage.py runserver
```
