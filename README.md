# flecs-particle-instantiating
Project to stress test Entity Component Systems (ECS) in a real-time simulations.
This repository features a particle system with 500000+ running at 100fps on conservative harware (intel i7 10th gen and no dedicated GPU). We are able to send data efficiently to the GPU via instantiating particles. 
Using a flecs query we find the first entity with a matrix component, and send the rest of the array to the GPU buffer.

We used the flecs framework for ECS and Raylib as a graphics library.

https://www.flecs.dev/flecs/

https://www.raylib.com/