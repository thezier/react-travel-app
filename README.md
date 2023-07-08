![#Travel App](readme-imgs/TRAVENTURE.png)

## Overview

This travel app allows the user to add travel locations with an image, url, location, tags and more to a board. A pop form allows the user to input this information.

This was my first time using Routes in React in order to display different pages.

I used DataStax (https://www.datastax.com/) for creating the database.

![Screenshot](readme-imgs/travel%20app.jpg)
![Screenshot](readme-imgs/travel%20app%202.jpg)

## Technologies Used

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![ApacheCassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white)

![GitHub top language](https://img.shields.io/github/languages/top/thezier/react-travel-app)

## Approach Taken

For the posts, I created a Card component to display all the information for each post.

![getLocation code snippet](readme-imgs/card.svg)

After fetching the data:

![getLocation code snippet](readme-imgs/data.svg)

Each post was then mapped to the dashboard.

![getLocation code snippet](readme-imgs/posts.svg)

## Wins and Challenges

### Wins

Using components in React was actually very comfortable to me and made sense. Importing and Exporting between components felt fairly nartural.

### Challenges

It was a new experience to use the Document API on DataStax for storing and fetching JSON data. It was also my first time writting a JSON file for the default posts for this app.
Also, I ended up having an issue that took me a while to figure out until I finally found that it was a simple misspelled word. It was a good lesson to not rush through, but instead to be more careful in checking my work.

Creating the server side was a new experience for me as well.

## Map API

The API used was from MapBox (https://www.mapbox.com/)
