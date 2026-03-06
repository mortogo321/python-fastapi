ARG PYTHON_VERSION=3.13.5

FROM python:${PYTHON_VERSION}-slim as base

WORKDIR /app

COPY . .

RUN pip install --upgrade pip
RUN pip install -r app/requirements.txt
