# PONG game using python
I create a arcade game that can be palyed by two players in a single PC.
Features
Two-Player Gameplay: The game supports two players, each controlling a paddle using different sets of keys (arrow keys for one player, and 'W' and 'S' keys for the other).

Ball Movement: The ball moves across the screen, bouncing off the walls and paddles. Its speed increases gradually as the game progresses.

Collision Detection: The game detects collisions between the ball and the paddles. When a collision occurs, the ball bounces off the paddle in the opposite direction.

Score Tracking: The game keeps track of each player's score. The scoreboard updates in real-time whenever a player scores a point.

How to Play
Clone the repository to your local machine.
Ensure you have Python installed.
Run the main.py file to start the game.
Player 1 controls the right paddle using the up and down arrow keys.
Player 2 controls the left paddle using the 'W' and 'S' keys.
Hit the ball with your paddle to keep it in play.
Earn points when your opponent misses hitting the ball.
The game continues until you decide to exit.


Files
main.py: The main Python script that initializes the game and controls the game loop.
paddle.py: Contains the Paddle class, which defines the behavior of the paddles controlled by players.
ball.py: Defines the Ball class responsible for moving and bouncing the ball.
scoreboard.py: Implements the Scoreboard class to track and display the players' scores.
Dependencies
Python 3.x
Turtle module (built-in with Python)
Contributions
Contributions to improve the game, add features, or fix bugs are welcome. Fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Author
Vasanth Marimuthu

Acknowledgments
Special thanks to the creators of the Turtle module for providing an easy-to-use graphics library for Python.
