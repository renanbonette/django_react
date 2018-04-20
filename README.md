# Integração entre React.js e Framework Python Django


## Dependências

```
Python 3
pip
django
virtualenv
nodejs
npm
```
## Run

```
mkdir folder_name
cd folder_name
git clone git@github.com:renanbonette/django_react.git
virtualenv venv
source venv/bin/activate
pip3 install django
cd django_react/
python3 manage.py migrate
python3 manage.py createsuperuser
cd frontend/
npm install npm run build
cd ..
python3 manage.py runserver
```