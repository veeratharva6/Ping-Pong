How To Run?

    Step 1: Click this link https://github.com/veeratharva6/Ping-Pong/archive/refs/heads/main.zip to download this project

    Step 2: Save this file on your computer and open your terminal

    Step 3: Use cd to navigate to the project folder

    Step 4: Compile using javac PongGame.java

    Step 5: Run the program using java PongGame



Project Description

    The goal for this project was to improve my software development skills 
    by creating a fun game called Ping Pong. This is a multiplayer game of Ping Pong 
    which is developed compeletly using Java.


Approach / What I did

    I began by splitting this projet into two steps. 
    
    Step 1 involved creating all the necessary objects needed for this project. This meant creating:

        Paddle Objects 
        Ball Object
        Game Panel
        Game Frame
        Score Board

    Step 2 involved implementing the game physics.

        For this step I carefully implemented the reaction of the ball per contact with the paddle. 
        This meant the ball would speed up once in contact and the ball will move in a specific 
        direction based on where the ball came in contact with the paddle. I also implemented when each 
        player scores a point and used the scored board to display the score during the game.

    

Issues and Resolutions

    I came across several issues while developing this project. Issues involving the proper creation 
    of objects and mostly involving the game physics. 
    
    Issue

        This biggest challenge I faced was finding a way to make the ball objet change directions 
        when it came in contact with the paddle. Alongside the change in speed when it comes in 
        contact to create the game more challenging.

    Resolution

        To solve this issue I split the paddle into two piece where if the ball comes in contact 
        with the top half of the paddle then it moves in a randomw direction to the top of the 
        screen and vice versa. To increase the speed as the play continues, I added velocity to 
        the ball object everytime it contacted the paddle. Each contact with the paddle will add 
        10 more the direction the ball is headed and slows down as it contacts the arena and edges. 
    

What I learned



