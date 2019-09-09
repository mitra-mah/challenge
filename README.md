# challenge
new Repository 
create a Chatbot using Pusher Channels, JavaScript, Dialogflow, Ngrok Flask. 
Creating a virtual environment in python and activate the virtualenv with the below command:
 env/Scripts/activate
in Flask environment, add the following to the .flaskenv file:

    FLASK_APP=index.py
    FLASK_ENV=development
Instructing Flask to use index.py as the main entry file. To this end, Add the corresponding code to index.py to start up the flask.

Then install the libraries in requirements.txt.
Using OMDb API which is a RESTful web service to obtain movie information and add the API key to the .env file:

    OMDB_API_KEY=API_KEY

After that use Dialogflow, (a Google-owned developer of human–computer interaction technologies based on natural language conversations) and train it to have an API key. So we Go to Google Cloud Platform. Add the project_id to the .env file and copy our downloaded API key which is the JSON file ( My-Bot-*.json) to the main folder of the project. 

Now to set up a webhook, it will make a request to our webhook using the movie keyword and send the result back to Dialogflow.
To get details about a movie, add the webhook to Dialogflow. Since it is a localhost and Dialogflow can’t access it we can use Ngrok.

We created a free account in Pusher Channels to get API key and add Pusher keys to .env file.

we also created a simple interface to type a message and send. To this end, using Bootstrap to create the page and add the HTML code to templates/index.html and also add corresponding styles to style.css in static folder.

We tried to build a chatbot using Flask and Dialogflow and add realtime functionality to the chatbot using Pusher. 






