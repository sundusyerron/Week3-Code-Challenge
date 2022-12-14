# Week3-code-challenge

# Project Description
In this code challenge you will be working on flatdango

flatiron movie  you will be building out an application,
flatdango,that allows user to purchase movie tickets from the theater.


# Project Set Up

To use this repo on your machine requires some simple steps

open the Terminal command line: [CTRL+ALT+T]

Clone this repository

git clone

git@github.com:sundusyerron/Week3-code-challenge.git

Change Directory: 

(cd Week3-code-challenge)

(Optional) Open it in Visual Studio Code

code .

# Running the application

Run this command to get the backend started:

$ json-server --watch db.json

Test your server by visiting this route in the browser:

http://localhost:3000/films

Then, open the index.html file on your browser to run the application.

Write your code in the src/index.js file. The base URL for your API will be http://localhost:3000.


## Core Deliverable

As a user, I can:

    See the first movie's details, including its poster, title, runtime, showtime, and available tickets when the page loads. The number of available tickets will need to be derived by subtracting the number of tickets_sold from the theater's capacity. You will need to make a GET request to the following endpoint to retrieve the film data:

    GET /films/1 Example Response: `{ "id": "1",
    "title": "The Giant Gila Monster",
    "runtime": "108",
    "capacity": 30,
    "showtime": "04:00PM",
    "tickets_sold": 27,
    "description": "A giant lizard
    terrorizes a rural Texas community and a heroic teenager attempts to destroy the creature.", "poster": "https://www.gstatic.com/tv/thumb/v22vodart/2157/p2157_v_v8_ab.jpg" }`

    See a menu of all movies on the left side of the page in the ul#films element when the page loads. (optional: you can style each film in the list by adding the classes film item to each li element.) There is a placeholder li in the ul#films element that is hardcoded in the HTML — feel free to remove that element.

## Auther
project contributed by;
[sundus](https://github.com/sundusyerron/Week3-code-challenge)

# License
'ISC'