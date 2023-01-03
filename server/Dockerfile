FROM python:3.9.16-alpine
RUN mkdir /code
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt
COPY . /code/
ENTRYPOINT [ "python" ]
CMD ["app.py" ]
