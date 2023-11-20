
FROM python:3.9

RUN apt-get update && apt-get install -y python3

WORKDIR /app

COPY . /app

RUN /bin/sh -c pip3 install -U setuptools && pip3 install -r requirements.txt

EXPOSE 5000

ENTRYPOINT ["python3"]
CMD ["run.py"]


