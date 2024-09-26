# Vamos
Vamos


python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

python manage.py migrate

psql -h localhost -p 5432 -U unimauro -d coredb

core

django-admin startapp core

django-admin startapp user

python manage.py makemigrations

python manage.py migrate