FROM python:3.6.8-slim-stretch  

WORKDIR .

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .
CMD slicer serve slicer.ini
