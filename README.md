# Flight-Fare-Prediction-Web-App


<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<a href=""><img src="https://drive.google.com/file/d/1Mg7A9oLnE7U9vHtuwJ4oSWAN5L0gm4sC/view?usp=sharing" alt="Website-Link" /></a>

<div id="tags" align="center">
<a href="https://www.linkedin.com/in/rachit-narang-49a4ba193"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:rachitnarang1711@gmail.com?subject=Hi%20Rachit"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>&nbsp;
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#landing-page">Landing Page</a><li>
        <li><a href="#dataset">Data Set</a><li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#how-to-run">How to Run</a><li>
        <li><a href="#data-visualization">Data Visualization</a><li>
        <li><a href="predicted-price">Predicted Price</a><li>
        <li><a href="#deployment">Deployment</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

This is a Flask Based Web Application that takes End User's input like Source City, Destination City, Date of Ariival and Departure, Airline Details and Predicts the Fare The user has to spend to Travel from Source City to Destination City . 

## Landing Page 
![landing page](/static/img/screen%20.jpg)

## Dataset
The dataset was taken from [here](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh). It is also present in this repo (X_train, X_test, y_train, y_test).




### Built With

Folowing is the Tech Stack used to Build this Web Application 

* Front End - HTML, CSS, JS, BOOTSTRAP 
* Back End - Flask, Jinja Templating 
* Deployment - HerokuApp
* Model Trained with - RandomForestRegressor()
* Hyperparameter Tuning done with - RandomizedSearchCV()





<!-- GETTING STARTED -->
## Getting Started

Prior Knowledge of python and command line is required.

### Prerequisites
Dependencies that need to be installed
* Pandas
  ```sh
  pip install pandas
  ```

* Flask
  ```sh
  pip install flask
  ```

* Requirements
  ```sh
  pip install -r requirements.txt
  ```

* Scikit-learn
  ```sh
  pip install scikit-learn
  ```


### How to run
- Open terminal
- cd to the directory where this code is present
- Install requirements
- Run python app.py
- Open Browser(Preferably Google Chrome)
- Go to http://127.0.0.1:5000 (local host) (This link will be shown to you in the terminal)

### Data Visualization 
Following Visuals from the Graphs and Charts shows the Trends of fluctuating Prices of Flight Fares in accordance with Different parameters.
![data visualization](/static/img/data1.jpg)
![data visualization](/static/img/data2.jpg)

### Predicted Price
![predicted page](/static/img/predict.jpg)



### Deployment

_The model is deployed in a minimalist website design. It is hosted on Heroku._

1. The frontend is made by HTML,CSS,JS and Bootstrap.
2. It can be locally run using the command
   ```sh
   python app.py
   ```
3. Command file is made by the name 'Procfile'. This contains the bash commands for the Heroko server.
  
4. Finally all files are pushed to the Heroku server.

<a href="https://movie-recommender-sarang.herokuapp.com/">Movie Recommender</a>


### Connect With Me
<div id="tags" align="center">
<a href="https://www.linkedin.com/in/rachit-narang-49a4ba193"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:rachitnarang1711@gmail.com?subject=Hi%20Rachit"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>&nbsp;
</div>


<p align="center">
Made with 💖 by Rachit Narang</p>

