## INTRODUCTION 

I used HTML, CSS & JavaScript to build this. I built this mainly because I wanted to work on my CSS and JavaScript skills. 
I mainly focused on keeping it as simple as I could, keeping it so that anyone can play and enjoy it.


## TECHNOLOGIES 

             - HTML
             - CSS
             - JavaScript
             - VS Code


## FEATURES 

           - Play a classic Snake game directly in your browser
           - Control the snake and collect food to grow longer
           - Track your score as you play
           - Restart the game anytime using the restart button
           - Experience smooth and responsive gameplay


## KEYBOARD SHORTCUTS 

           -  Arrow Up → Move Up
           -  Arrow Down → Move Down
           -  Arrow Left → Move Left
           -  Arrow Right → Move Right


## THE PROCESS OF BUILDING

                         - Canvas Setup
                                       => Created a grid-based board using HTML <canvas>
                                       => Defined rows, columns, and block size
                         - Game Loop
                                       => Used setInterval() to continuously update the game state
                                       => Redraws the board, snake, and food every frame
                         - Snake Movement
                                       => Controlled using velocity (velocityX, velocityY)
                                       => Updated position based on keyboard input
                         - Food System
                                       => Randomly generates food positions within the grid
                                       => When the snake eats food:
                                                               > Snake grows
                                                               > Score increases
                         - Collision Detection
                                       => Detects:
                                                  > Wall collision → Game Over
                                                  > Self collision → Game Over
                         - Rendering
                                       => Snake drawn in green
                                       => Food drawn in red
                                       => Score displayed on canvas
                         - Restart System
                                       => Reset all variables to initial state
                                       => Allows replay without refreshing the page


## WHAT I LEARNED 

                 - How to use HTML Canvas for game rendering
                 - Handling keyboard events in JavaScript
                 - Creating a game loop using setInterval()
                 - Implementing collision detection logic
                 - Managing arrays for dynamic objects (snake body)
                 - Structuring a small project from scratch


## HOW CAN IT BE IMPROVED 

                     - Add sound effects 🎵
                     - Increase difficulty over time (speed scaling)
                    - Add pause/resume feature
                    - Improve UI with better animations and design
                    - Add mobile controls (touch support)
                    - Store high score using local storage


## PREVIEW 



https://github.com/user-attachments/assets/adcc9143-d30f-422c-bf15-feb44e12afd0

