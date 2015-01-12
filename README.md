# Flappy Salad
How to make Flappy Bird in Game Salad

## Start Here:

### Download this repository
Download [here](https://github.com/patmood/flappy-salad/archive/master.zip). This repo has all the instructions and graphic assets you will need.

### Download Game Salad
Create an account with Game Salad and download the editor here: http://gamesalad.com/download

### Create a new project
Change the platform from iPhone to `Game Salad Arcade` and choose a name/description

## Scenes
Game scenes are used to organize your project into separate parts. You might have a menu scene, a game screen, or a separate screen for each level. In this game we can use 1 scene.

## Actors
Actors are objects in your game that contain unique behavior. This makes it easy to reuse the same work over and over again so we dont repeat ourselves. An actor could be the player, an enemy, an obstacle, or even just a background.

### Add an actor

![add actor](screenshots/1_add_actor.png)

In the actors section, click the `+` button to add a new actor that we can use for the background. Double click the new actor to edit and drag the background in to the Game Salad editor.

### Add the backgroung actor to the scene
Drag the new actor with the background image on to the game screen and resize it to fill the screen.

Notice how the image is stretched. Open the actor again and Under the attributes, Change Graphics > Horizontal Wrap to `tile` so that it repeats over and over in the horizontal direction. Much better.

![change attributes](screenshots/2_actor_graphics.png)
