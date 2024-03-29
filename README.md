# Restaurant Reviews App

Restaurant Reviews App is a project that is required as an evaluation by [Udacity Advanced Web Front-End Nanodegree Program](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001). For this project, a repository with a good piece of ready-to-start code was provided. The code had a lot of issues. It was barely usable on a desktop browser, much less a mobile device. It also didn’t include any standard accessibility features, and it didn’t work offline at all.

See the [original repository](https://github.com/udacity/mws-restaurant-stage-1).

The requirements for this project were:
1. Convert the provided website, making it use a responsive design.
2. Implement accessibility features in the site's HTML (most of this HTML is generated by JavaScript functions).
3. Add a ServiceWorker script to store cached requests for all site assets so that all pages accessed by a user can be accessed again when the user is not connected to a network.

See the application working after the requirements have been implemented: https://webdavloper.github.io/restaurant-reviews

## Installation:

Clone this repository running `git clone https://github.com/webdavloper/restaurant-reviews` or download this project through the repository settings.

## Running the application locally

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/).

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
