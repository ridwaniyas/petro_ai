web: gunicorn config.wsgi:application
worker: celery worker --app=petro_ai.taskapp --loglevel=info
