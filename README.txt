Xinyu and Bruce can keep all our notes regarding Xinyu's game idea here...

Xinyu: I tried them, and they really worked: the box is in the middle of the screen when making any movements. But there are some other problems. The camera doesn’t actually follow the cube when it is moving away from the screen or towards the screen.

Bruce: Yes... right now the zoom with the camera is separate from the player movement. We can connect them but I think it will be good to be able to Zoom away from the player so you can see more context of the situation.
 
Xinyu: It gives me a sense of rotating around the cube but not following the cube. I think this is quite complicated. Can this be improved?

Bruce: We need to fix the camera so it can follow the player into negative Z space (right now, it stops at the center of the room).
Bruce: We can keep working on how we want it to behave.
 
Xinyu: Also, I have some ideas about developing the game. I think it is more like a player avoiding the dangerous traps in each closed room, like rocks (spheres) or some weapons (cylinders). Have a sound when the cylinder is shot.

Sure. I figured that was your main theme.
 
Xinyu: The moving objects in the room can be such dangerous traps. More specifically, like rolling rocks and flying knives.

Bruce: OK... we can model rocks and knives at some point, but for now we can use the primitives and get them behaving as you want them to behave. We can focus on collisions tomorrow so we know when the player is being injured or losing the game.
 
Xinyu: The player should avoid these moving objects. There are also objects not moving, they are the environment in the room, like walls, small ramps, stable things. They are like obstacles, player can touch them and don’t have to avoid them.

Bruce: You can design that as geometry and then we can create the available movements allowed with respect to them.
 
Xinyu: The goal is to walk through obstacles while avoiding traps and find the way out the room. Is this idea ok?

Bruce: Yes... the idea is great for you to learn about everything you need to get started with 3-D games. Let's build a schedule in terms of our order of game development. I think we can at least get one of each item working so you have code you can duplicate.
