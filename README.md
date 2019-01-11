# Hood App
 This is a web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts.
 # Developer
 Vinny Otach
 # Setup and Installation
 <ul>
 <li>
Clone the Repo uding the following command: git clone https://github.com/vinnyotach7/Neighbour-Hood.git</li>
<li>Activate virtual environment using python3.6 as default handler by running python3.6 -m venv virtual then enter the virtual environment using source virtual/bin/activate.</li>
<li>Download the latest version of pip in the virtual environment: $ curl https://bootstrap.pypa.io/get-pip.py | python</li>
<li>Install all application dependancies pip install -r requirements.txt</li>
<li>Create the Database -On the terminal,run psql
<ul>
<li>Create a database by typing CREATE DATABASE ----;</li>
</ul>
<li>Create a .env file and add the following:
<ul>
<li>SECRET_KEY = secret_key</li>
<li>DB_NAME = ???????</li>
<li>DB_USER = Username</li>
<li>DB_PASSWORD = your db password</li>
<li>DEBUG = True</li>
</ul>
<li>Run Initial Migration python3.6 manage.py makemigrations <name of the app> python3.6 manage.py migrate.</li>
<li>Run the app python3.6 manage.py runserver Open terminal on localhost:8000</li>

# User stories
As a user I would like to:
<ul>
<li>Sign in with the application to start using.</li>
<li>Set up a profile about me and a general location and my neighborhood name.</li>
<li>Find a list of different businesses in my neighborhood.</li>
<li>Find Contact Information for the health department and Police authorities near my neighborhood.</li>
<li>Create Posts that will be visible to everyone in my neighborhood.</li>
<li>Change My neighborhood when I decide to move out.</li>
<li>Only view details of a single neighborhood.</li>
</ul>

# Technologies Used
<ol>
<li>python3.6.7</li>
<li>HTML</li>
<li>Bootstrap4</li>
<li>postgresql</li>
</ol>

# License
MIT license copyright(c) 2018 vinny otach
