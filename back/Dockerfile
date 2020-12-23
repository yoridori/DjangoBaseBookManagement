FROM python:3.8
ENV PYHONUNBUFFERED 1

WORKDIR /server
ADD . /server/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt