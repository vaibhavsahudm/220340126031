FROM python:3.10.6-alpine3.16

LABEL maintainer="220340126031/vaibhavsahudm"

# sets working directory inside container
WORKDIR /usr/src/pythoncodes

# copy from host to container directory
COPY sqaureNum.py /usr/src/pythoncodes

CMD ["python3", "sqaureNum.py"]

# sudo docker build -t squareNum:v1 .
# sudo docker run -it squareNum:v1
# or sudo docker run --name addcal -it squareNum:v1
