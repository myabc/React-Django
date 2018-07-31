# React-Django app
Simple setup for a React-Django web app. See tutorial here: https://medium.com/@nicholaskajoh/heres-a-dead-simple-react-django-setup-for-your-next-project-c0b0036663c6.

## Setup

1. Download/clone this repo:

       mkdir ~/python-sites
       cd ~/python-sites
       git clone https://github.com/myabc/React-Django.git

2. Create and activate a virtual environment:

       cd ~/React-Django
       virtualenv .

       source ./bin/activate

3. Install Django and other dependencies:

       pip install -r requirements.txt

4. Migrate the Django app database:

       python manage.py migrate

4. Run the Django app:

       python manage.py runserver

6. Install React dependencies with

       yarn install

7. Run React app with `yarn start`.
8. Build React app using `yarn run build`.

## Deploy
Read my tutorial on deploying this app to Heroku here: https://medium.com/@nicholaskajoh/deploy-your-react-django-app-on-heroku-335af9dab8a3.
