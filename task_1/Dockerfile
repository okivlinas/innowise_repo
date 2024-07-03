FROM python

WORKDIR /app

EXPOSE 8002

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY first.py .
COPY rooms.json .
COPY students.json .

CMD ["python", "first.py"]