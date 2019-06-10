# docker build -t my-python-app .
# docker run -it --rm --name my-running-app my-python-app
# https://hub.docker.com/_/python/
FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# CMD [ "python", "./your-daemon-or-script.py" ]
