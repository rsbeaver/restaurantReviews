Restaurant Reviews App (First Stage)
===============================

# Table of Contents

* [Description](#description)
* [Project Instructions](#project-instructions)
* [Run the Application](#run-the-application)
* [Code Dependencies](#code-dependencies)

## Description

* Created as project 5 for the Udacity Front-End Developer Nanodegree.

## Project Instructions

In this project, a static webpage that lacks accessibility was given to be converted into a mobile-ready web application. This is my end-design, and is responsive on different sized displays and is accessible for screen reader use. The complete Restaurant Reviews app ( stage 1 and stage 2) will feature a service worker to create a seamless offline experience for users.

## Run the Application

You have options to run this project:

1. Open it [here](https://rsbeaver.github.io/restaurantReviews/)

2. Run it locally
     Download as .zip file or clone this project:
     $ git clone https://github.com/rsbeaver/restaurant-review

* THEN...

You will need an HTTP server to bring up the site files on your local computer.  If you are using chrome, you can easily add the Web Server for Chrome app by clicking on the app icon (usually in the upper left of the menu bar). I found that using one of the http url addresses rather than the localhost port worked better.  When starting the server, simply select the folder where you stored the files you cloned or downloaded (and unzipped) earlier.

* If you are using a browser other than chrome, you will need to set up your own web server.  Python has some simple tools to do this, and you don't even need to know Python. For many users, it's already installed on your computer.  In the folder where you store the cloned or unzipped files, start up a simple HTTP server to serve up the site files on your local computer.

* In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

* With your server running, visit the site: `http://localhost:8000`.

## Dependencies

* [Project Restaurant Reviews (Stage 1) - Starter Code](https://github.com/udacity/mws-restaurant-stage-1)
* [Normalize.css](https://necolas.github.io/normalize.css/)
