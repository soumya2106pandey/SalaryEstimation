## Salary Estimator
This is project to elaborate how Machine Learning Models can be used to determine salary based on factors like interview score, test score and experience.

### Project Structure
This project has four major parts :
1. model.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.
2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3. request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.
4. templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.

## Run app.py using below command to start Flask API
By default, flask will run on port 5000.

## Navigate to URL http://localhost:5000 (local Host)

THe model is hosted on Amazon ElasticBeanstalk and the below link could be used to view results:
http://hh-env.eba-qtwas2vm.us-east-2.elasticbeanstalk.comhttp://hh-env.eba-qtwas2vm.us-east-2.elasticbeanstalk.com/


The model is trained using custom dataset provided above (Hiring.csv) static and templates contain the web page code and application.py is the Flask app.

For e.g. values 2, 9, 6 for experience, test score and interview score resp predicts the salary as approx Rs 53290.
