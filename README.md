# BankNoteAuthentication-(end-to-end)
A simple machine learning web application that predicts the authenticity of a bank note using Random Forest Classifier.

## Getting Started
gigt clone https://github.com/reg-11/BankNoteAuthentication-end-to-end-Project-.git


## Running Web Application (Docker)
docker build -t banknote:latest . <br>
docker run -d -p 5000:5000 banknote

## Tools
- flask
- streamlit
- Sklearn
- Docker

## If not using Docker (Other way)
activate your virtualenv <br>
run: pip install -r requirements.txt

## Running Web Application (Local Server)
FLASK_APP=flask_app <br>
flask run  (for flask app) <br> <br>
streamlit run app.py  (for streamlit app)


## Credits
https://github.com/krishnaik06/Dockers
