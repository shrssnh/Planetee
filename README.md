# A Space Exploration Game 

## First things first
This is not the entire project. Due to size limitations, the bare minimum (assets and playable build) has been uploaded here on github.

## About the Game
The idea for the game came up when we were exploring unity terrain and built something that looked earthly yet quite alien.

We then learnt to work with the URP pipeline to insert a custom shader (you can find them in the 'Materials' folder) on the camera that takes the image, extracts the luminosity, posterizes it to 4 levels and applies a two tone effect to it. Post processing is done on top to give a nice glow effect.

We then went on to create AI scripts for the enemies. A script to handle puzzle elements was also created for an added challenge.

## YOU WILL BE CONFUSED
We have given no explanation in the game about whatever is happening so here it is:

- You are a space cop. You were attacking some space pirates but crashed in the battle.
- You have to repair your ship and escape.
- Collect 3 wires (close to the spawn point)
- Collect fuel tank (between the rocks)
- Collect planet fluid (behaves as fuel) (follow sequence of rocks you'll find the lake)
- You have to hold E for 10 seconds to collect fuel. It collects fuel, even if the timer does not update.
- Collect Thruster (beyond the lake is the pirates mothership, where the thruster is).
- Once eveerything is collected, you will automatically transport to the next level (snow world) which does not work. You can also go to this level from the main menu.
- You can access the main menu by pressing the right shift (escape didn't work on my machine for some reason).
- Use left click to kill the enemies. They need 3 bullets to die but your bulets are less likely to hit the further away you are. Your health is on the bottom right.

## Credits
The Terrain was generated in unity, but grass textures were taken from google image search. Spaceship models and other (unused) models were taken from TurboSquid. Music used is the Mass Effect Map theme and Selusa Secundus from the Elder Scrolls series.
