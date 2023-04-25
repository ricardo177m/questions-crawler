# Questions Crawler

A simple PDF Crawler to extract questions from exams and parse them to JSON format.

## Installation

- Install `virtualenv` if you do not have it: `pip install virtualenv`
- Create the virtual environment: `python3 -m venv env`
- Activate it: `source env/bin/activate`
- Install dependencies: `pip install -r requirements.txt`

## Usage

- Copy .env.example to set your environment variables (`cp .env.example .env`)
- To add the extracted data to the database: `python3 import_to_database.py`

