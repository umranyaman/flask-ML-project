
# Deployment of Machine Learning Model into AWS Cloud Servers

This project is a spam detector API developed using Flask framework and deployed on AWS Elastic Beanstalk. The API uses a machine learning model to classify whether a given text message is spam or not.

## To run the project locally, follow these steps:

Clone the repository to your local machine

Create a virtual environment using virtualenv or conda

Activate the virtual environment

Install the dependencies using pip install -r requirements.txt

Run the Flask app using flask run

The API will be available at http://localhost:5000.



## Deployment

The project is deployed on AWS Elastic Beanstalk using the eb command-line interface. To deploy the project to your own Elastic Beanstalk environment, follow these steps:

Create an Elastic Beanstalk environment with Python platform

Clone the repository to your local machine

Install the Elastic Beanstalk CLI using pip install awsebcli

Initialize the Elastic Beanstalk CLI using eb init

Create a new application version using eb create

Deploy the application using eb deploy

