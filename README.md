#TPO Website

![home](https://user-images.githubusercontent.com/46722282/93333018-5a039100-f840-11ea-82af-5586d27a4308.png)
<h2>Getting Started</h2>
<p>Steps:</p>
<ol>
<li>Clone/pull/download this repository</li>
<li>Create a virtualenv with <code>virtualenv env</code> and install dependencies</li>
<li>Configure your .env files.</li>
<li>Activate the virtual env using <code>Scripts/activate</code></li>
<li>You've setup the virtual env and you're good to run the project.</li>
</ol>
<h2>Installation</h2>
<pre>pip install django</pre>
<pre>pip install django-bulma</pre>
<h2>Login</h2>

You can access the django admin page at http://127.0.0.1:8000/admin and login with username 'admin' and the password as admin123.
Also a new admin user can be created using
<pre>python manage.py createsuperuser</pre>
<h2>Usage</h2>
Go to TPO_website folder and run
<pre>python manage.py runserver</pre>
Then go to the browser and enter the url http://127.0.0.1:8000/


<h2>This project includes:</h2>


->Our project consists of sign in and login page for students as well for admin.

->Then comes the upcoming events section where the students can login for the events such as Training for Internships, Machine Learning, AR/VR and so on.

->Then it displays the list of current companies where you can apply for the role that you wished for.

->Also, it shows the results of the current rounds of the company.

-> We have also designed statistics of the previous years using chart.js and the user can also download the report of previous years.
