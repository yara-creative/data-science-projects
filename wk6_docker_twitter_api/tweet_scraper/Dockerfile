FROM python:3.6-slim

WORKDIR /app

ADD /. /app

RUN pip install --upgrade pip
RUN pip install --trusted-host pipy.python.org -r requirements.txt

CMD ["python","tweet_scraper.py"]
