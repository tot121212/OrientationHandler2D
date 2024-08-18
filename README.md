This is a simple left/right 2D Orientation Handler for Godot 4.2.2

To use:
  ![image](https://github.com/user-attachments/assets/a2ccfba6-49f9-4fde-b74a-715ce3181475)
  - Assign what the root of the scene tree is
  - Add whatever node(s) you wish to flip to the array

NOTE:
Whatever nodes are added to this array must not have their rotation changed.
Instead, simply utilize the root node for all rotation changes, or add said array nodes as children to another Node2D.
(As you can see in the example photo, I am not worrying about rotation on the Lizard, hehe)
