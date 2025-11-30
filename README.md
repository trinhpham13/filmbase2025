Start project: 
$ git clone https://github.com/trinhpham13/filmbase2025
$ cd filmbase2025
$ git checkout main
$ python -m venv .venv
$ . .venv/bin/activate
$ python -m pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py import_films
$ python manage.py runserver
