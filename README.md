# UnrealGame

A 3D Co-op Top Down Shooter Game using Unreal as a Game Engine.

- All Meshes, Animations and Textures are from the Unreal Asset Store.  
- The Game is based on a beginner tutorial of an Unreal course (Twin Stick Shooter).
- It is a basic shooter game where the players have to survive all waves of enemies. 
***
- [Features to implement:](#features-to-implement)
- [Weapon System](#weapon-system)
- [Character System](#character-system)
  * [Healthcubes](#healthcubes)
- [Stage Design](#stage-design)
  * [Stage Level](#stage-level)
  * [Spawn Manager](#spawn-manager)
- [Input:](#input)

***

#### Features to implement:
* [x] Stage design
* [x] UI Design
* [x] Finding Assets
* [x] Input System Design
* [x] Physics System

***
#### Weapon System:
The weapon is attached to the player. It has basic values for 'Firing Rate' and 'Damage'
  - Damage = Damage the Weapon will do on an enemy player per projectile hit
  - Firing Rate = The timeframe which is needed for one projectile to be shot
 ***
#### Character System:

##### Healthcubes
  - Healthcubes can be picked up by each player simply by walking/colliding against them
  - The players maximum health is 100 (Life Points)
    * If the player has maximum health when picking up a health cube it will stay at 100 health
    * Else the player will gain 10 Life Point
***
#### Stage Design:
##### Stage Level: 
  - There are two difficulty levels for the stage (easy and hard). There will be more enemies in the harder one. Furthermore, the stages  differ slightly. 
  
##### Spawn Manager 
  - Items and enemies will be spawn randomly on the map
  - There is a spawn limit, limiting the objects to be spawned on the map depending on the stage level and the current wave
  
***
#### Input:
For 1 Keyboard and 1 Gamepad -> see in game description of 'How to play'
