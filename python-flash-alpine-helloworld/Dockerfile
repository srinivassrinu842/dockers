FROM python:3.7-alpine
WORKDIR /app/
COPY src/ .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python3.7", "./app.py"]
