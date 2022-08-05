# flappybird
The goal of the game is to get through the opening in the obstacles without colliding into them. The game is implemented in C++. The case study discusses the use of simpler motion and modification to build the abstraction.

The user can interact with the game using keyboard. The game is a 2D game with the purpose to keep the dot moving forward.

For the game to feel like Flappy Bird, the focus is given on the gameplay. The two essential elements that the game needs to get right are the “bird” and the “pipes”. Specifically, the bird has to move like a Flappy Bird, and our pipes must generate and move exactly as their Green counterparts.

*We made this project so that we could give our best to show what we have learned.*

The main objectives of this project are:

* To play the famous game flappy bird in computer.

* To make it user friendly. 

* To provide an easy interface. 

* To entertain people in their leisure time.


### User Defined Functions:
1. Birdmovementmouse - to regulate the gameplay and movement of the bird using the mouse.

2. Birdmovementkey - to regulate the gameplay and movement of the bird using the keyboard. 

3. Renderbitmapstring - to give the values of initial introduction screen 

4. Drawscore - to keep updating the score as and when the game progresses. 

5. Introscreen - to display the introduction screen. 

6. Gameoverscreen - to display the score screen when the game is over. 

7. Menu - to display menu.

8. Display - to display the introduction screen, the gameover screen and other functions. 

9. Resetgame - resets the game to its initial state. 

10. Drawpipe - draws the obstacles in the game, their specific axes and the position to where they are initialized. 

11. ObstacleCreate - to check whether the bird has crossed the particular pipe or not and increase the score corresponding to it. 

12. drawBird - to draw the bird using general OPENGL functionalities and initialise its state and starting axes. 

13. Birdcollision - to fix the final state and return the collision when the bird comes in contact with the pipespawner 4. 

14. Birdfly - to help the bird move longitudinally by moving its axes, position and keep a check of the obstacle in front to smoothen the bird’s ride. 

15. Birdfall - receive the value from birdcollision function when the bird comes in contact with the pipespawner, fix the final state and reset the game. 

16. Birdphysics - to see to the movement of the bird, its flaps, its wings and the angle of those wings.
