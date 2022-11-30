# Bristol-Stools
Footstools with images of Bristol on them

git clone https://github.com/mmw111161/Bristol-Stools.git
python3 -m venv .venv
source .venv/bin/activate
pip install wagtail
pip install -r requirements.txt 
python3 -m pip install django-debug-toolbar
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
user/password: melvyn/admin
python3 manage.py createcachetable
python3 manage.py runserver
