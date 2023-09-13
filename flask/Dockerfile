FROM python:3.11.4-alpine

# Set the working directory to /app
WORKDIR /app

# Install the dependencies
ADD requirements.txt /app/requirements.txt
RUN pip3 install -r requirements.txt

# Copy the current directory contents into the container at /app
ADD . /app

CMD ["python3", "app.py"]