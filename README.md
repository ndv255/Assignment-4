# Assignment-4

How to Play
The goal of this game is to make it to the chicken coup on the right side of the map before the fox gets you. You may collect the stars along the way try to collect as many as you can to become a completionist.

Controls
Space-jump
a-left
d-right


requirements
1.Map is made out of tiles
2.The plater has a collision shape and can move also they can only jump when they are on the floor
3. Both the fox enemy and the main playable character have animations
4.The enemys have pathfinding where they will chase the player so long as the player is inside of the navigation area2d
5.There is navigation layers over the tilemap
6. The enemy have a nabigationAgent2d that forces it to stay in the area and a speed in which they will follow the player
7.The fox avoids obstacles but also will still pathfind around them
8. There is two particle effects I couldn't decide gameplaywise what to use it for so I just made it so that the fire has the smoke particle and the water has some splash particles
9. You can interact with the collidable objects and the collectable stars along with the chicken coup
10.There is collision and there is areas where the player is not able to walk through as well as the fox
11.There is collectable stars that increment a score connected to the player
12.There is gravity and jumping connected to the player
13. There is a Minimal UI just to display how many stars have been collected
14. I wanted the game to remain simple but well done I would like to think that there is no bugs that are appearent to me.

side note all code was written in C#
also all of this was done in a single day So I didn't really make commits as I went I just figured I'd hunker down and do the whole assignment.


In this I used example files from the class such as the start up files for this and the 2dtile demonstration project that was worked on for notes.I also used copliot AI for debugging and assistance while writing code. ChatGPT was used at the end to clean up the code and make it better formatted but was also used at somepoint to understand why a certain bit of code was not working.
