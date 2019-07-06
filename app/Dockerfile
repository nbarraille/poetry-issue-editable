FROM python:3

RUN pip install pipenv

COPY . /app
WORKDIR /app/app

RUN ls -ahl /app/app

RUN pipenv install --system --deploy

