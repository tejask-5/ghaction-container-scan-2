FROM alpine:3.9
RUN apk add bash openssl
WORKDIR /code
ADD requirements.txt /code/
RUN pip3 install -r requirements.txt
ADD . /code/
RUN chmod -R 775 /code/
EXPOSE 5001 22
