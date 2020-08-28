# Self-Driving-Car-Simulation-using-Genetic-Algorithm-in-Unity-3D
In this project we have trained an evolving Neural network by using Genetic Algorithms in Unity Game Engine using the ML-agents provided by them. By repeated simulation of the agent in the environment, using this we have created an agent which learns unique features from the environment based on its input and generates a forecast permitting the vehicle to drive without requiring external commands from the player. For simplicity purposes the ability of the agents to brake or reverse was not added.

Note- This project was created on Unity3D version 2018.2.14f1. You will need Barracuda package (ver 0.4).

The simulation environment was chosen to be a forested environment.

![simulation environment](https://user-images.githubusercontent.com/64498789/91141920-adfdd880-e6cd-11ea-9bd3-e029d4dec871.png)

Closeup of the environment.

![closeupshot](https://user-images.githubusercontent.com/64498789/91141813-a76f6100-e6cd-11ea-8d9b-af1dc5e170de.jpg)

Raycasts emerging from the agents are used to calculate the distances from the obstacles and accordingly the agents turn without crashing.

![raycasts](https://user-images.githubusercontent.com/64498789/91141854-a9d1bb00-e6cd-11ea-9cc7-d0209264b353.png)

A bunch of agents spawn at once in which many will crash however as the generation increases, the performance of the agents gets better as well.

![population of cars spawning](https://user-images.githubusercontent.com/64498789/91141841-a9392480-e6cd-11ea-807d-250cc66a00c9.jpg)

This project was created as a fun project while exploring unity3d game engine and ml-agents.
