FROM python:3-onbuild
RUN apt-get update
COPY . /usr/src/app
EXPLORE 8080
CMD ["python", "api.py"]
