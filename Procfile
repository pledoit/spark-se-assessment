web: gunicorn app:app
release: python manage.py db upgrade
heroku ps:scale web=1
