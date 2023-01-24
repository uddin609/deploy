FROM python:3.8-slim-buster

WORKID /app

COPY . /app

RUN pip install -r requirements.txt

CMD ["python","manage.py","runserver"]
