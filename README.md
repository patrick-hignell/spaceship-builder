## Spaceship Builder

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot12.png?raw=true)

For this Unity project I wanted to make a game in which the player can create a working modular spaceship including the internal wiring and thruster placement.

The game currently features three different gravity systems depending on the environment:
1) Free floating when in space.
2) Downward gravity when the player is in a spaceship relative to its rotation.
3) Gravity applied towards a planet's centre when within its gravitational pull.

This also requires different movement and rotation logic depending on the different environments, for example to prevent the look direction from being locked around the y axis when in space.

In the future I would like to add features such as the player being able to make their own circuit boards with logic gates to determine the behaviour of the ship when interacting with components such as the helm. I would also like to add power and fuel as resources the player will have to manage within their ship. Ultimately I would like to add asteroid mining, crafting and automation as the main gameplay objectives.

## Screenshots

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot1.png?raw=true)

The player can add to their spaceship by activating blueprint mode and will be able to see a preview of where the new room will be added.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot2.png?raw=true)

There is currently several rooms to choose from including corridors, stairs, corners and t-junctions.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot4.png?raw=true)

The player can also add thrusters to the exterior of the ship which when activated will allow for the ship to move through space by applying force at their position to the ships rigidbody.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot3.png?raw=true)

The player can enter the ship, triggering the player to transition from free floating to ship gravity.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot5.png?raw=true)

Wires can be picked up and extended from the ships helm and then attached to the internal nodes of the thrusters.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot6.png?raw=true)

The color of each wire identifies which helm output is connected to which thruster.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot7.png?raw=true)

The wires are rendered using a curved line renderer asset in combination with a custom script controlling the positions of its nodes depending upon the distance and direction between the start and end of the wire.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot8.png?raw=true)

When the player is at the helm the player can then activate different wires depending on which key is pressed.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot9.png?raw=true)

The activated wire then activates the thruster that it is connected to. The amount of torque being applied to the ship is dependent upon the position of the thruster relative to the ships centre.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot10.png?raw=true)

Currently you can move between several small planets at high speeds.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot11.png?raw=true)

Once approaching a planet or asteroid, the player and the ship will be affected by the ships gravity and you can attempt to land on its surface.

![main screenshot](https://github.com/patrick-hignell/spaceship-builder/blob/main/public/images/screenshot12.png?raw=true)

When exiting the ship, the player then switches to planet gravity, being pulled toward the planets centre and movement is tangential to that direction.

## Next Steps

- add asteroid field and random asteroid generation

-	add circuit boards with logic gates

-	add fuel and power resources

-	add mining nodes

-	add crafting and automation

-	add story mode
