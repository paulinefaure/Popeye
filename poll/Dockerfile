FROM python:3.7
WORKDIR /code
ENV FLASK_APP app.py
ENV FLASK_RUN_HOST 0.0.0.0
COPY requirements.txt .
COPY . .
RUN pip install -r requirement.txt
EXPOSE 80
CMD [ "flask", "run"]