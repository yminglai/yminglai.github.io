<!-- ---
layout: page
title: Darts App
description: Experience competitive darts online with the Darts Game Website. Featuring real-time scoring, multiple game modes, and a dynamic leaderboard, it transforms traditional darts into an engaging digital experience.
img: assets/img/darts-image.png
importance: 1
category: fun
---

## Description
The Darts Game Website is a dynamic web application designed to enhance the experience of darts competitions. It provides a user-friendly interface for dart players and enthusiasts to engage with the game more interactively. The core features of the website include:

# Countdown Game

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-countdown.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-count-down-recommendation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-winPage.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Countdown Game - Interactive screens for game setup, real-time scoring, and winner announcement in the Darts Game Website.
</div>


### Countdown Game in Darts Game Website

This image presents the Countdown functionality of the Darts Game Website. It features three main interfaces:

- **Create Game**: Users can set up a new game by selecting the game type as "Count Down," choosing the starting score (e.g., 301), and specifying the number of players. Player names can be customized in the dropdown menus.

- **Game Interface**: Displays a live scoreboard where player scores are updated in real-time. The interface includes buttons for recording dart scores and shows calculated averages and possible score combinations (e.g., T20 + T15 + D20).

- **Victory Screen**: Announces the winner with their final score and average score per turn. This screen provides options to start a new game or return to the homepage.

These interfaces demonstrate the application's capability to manage and display scores dynamically, enhancing the user experience during a dart competition.


# High Score Functionality

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-highestscore.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-highscore.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/darts-winPage.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    High Score Game - Interactive screens for game setup, real-time scoring, and winner announcement in the Darts Game Website.
</div>


### High Score Game in Darts Game Website

This image displays the High Score functionality of the Darts Game Website. It illustrates three primary interfaces:

- **Create Game**: This section allows users to initiate a new game by selecting "High Score" as the game type, choosing the number of rounds (e.g., 4), and the number of players (e.g., 2). Players can input their names in the provided fields.

- **Game Interface**: This interface shows a real-time update of scores for each player. Here, player scores are displayed alongside the number of wins per total games played. The example shows MingMing with a score of 95 and YangYang with a score of 180 after one round.

- **Victory Screen**: This screen announces the winner of the game, MingMing in this case, with a highlight on their average score per turn. It also offers options to start a new game or return to the homepage.

This layout is designed to provide a seamless and interactive user experience, keeping track of scores and rounds efficiently during gameplay.


### Core Features
- **Live Scoreboard**: Allows players to view and update scores in real-time during a game. Supports different game modes such as Countdown and Highscore, adapting to various play styles and rules.
- **Leaderboard**: Maintains a continuously updated leaderboard displaying win data, helping to foster a competitive environment.


## Installation
The backend of the app connects to a database using PHP for dynamic data management. The installation requires setting up a MySQL database and configuring the connection settings in the `connect.php` file. Ensure this file is included in the `.gitignore` to protect sensitive information.

## Deployment
To deploy the application in a production environment:
1. Navigate to the directory where the application is hosted.
2. Use Git commands to pull the latest version from the production branch:
```
git pull production prod
```



## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Repository
[mlyann/darts-game-website](https://github.com/mlyann/darts-game-website) 
(Private now but ready to open source soon!)

This project aims to provide dart players with a seamless and interactive experience, enhancing both the competition and enjoyment of the game.

{% raw %}

```php
<?php
//connect
$servername = "";
$username = "";
$password = "";
$database = "";

$conn = new mysqli($servername, $username, $password, $database);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
```

{% endraw %}


## Developer
* Minglai Yang
 -->
