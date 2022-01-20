# class-27-v3


 Create an animated sprite from a GIF.
● Create SpriteSheet for boat animation.
● Create SpriteSheet for broken boat animation.
 -----------------------
 The class uses Piskel, a free online editor for animated sprites,
 
 
 Create a SpriteSheet for a moving boat.
● Add moving boat animation to the boat.

-----------------------


 we’ll be adding the animations to the boats to give it a feel as if the boat is moving on the water.
We already have some of the images loaded in the assets folder.

boat.json file.
we have a frames key and its value is an array that contains multiple objects with different positions of the images.
an object has multiple keys such as position, rotated, trimmed, spriteSourceSize and sourceSize.
The most important one is the position as it contains the position of the images.

boat.png file.
In this file you can see that we have 4 different frames of the boat, each has a different action.

-------------------------
 
Declare variables in sketch.js file

We’ll first create a boatAnimation array.

We’ll also declare two variables: boatSpritedata and boatSpriteSheet.

boatSpritedata will contain data from JSON.
boatSpritesheet will contain the images.


Load Images and JSON in preload() function
