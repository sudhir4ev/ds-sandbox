FROM python:3.10-slim

WORKDIR /app

RUN pipx install poetry

COPY pyproject.toml poetry.lock ./

RUN poetry install --no-root


