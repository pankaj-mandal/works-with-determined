FROM python:3.8

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY train.py /app

ENV PYTHONUNBUFFERED=1

RUN apt-get update;apt-get install -y vim
