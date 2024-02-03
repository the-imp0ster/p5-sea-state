# Sea State Visualization with p5.js

This project simulates the appearance of waves under different sea state conditions using p5.js.


The sea state is categorized on a scale from 0 to 10: Sea state 0 corresponds to a calm sea, while sea state 10 corresponds to extremely rough conditions.


### Wave Generation

A slider input dynamically adjusts the sea state level. 

Each wave is generated using a combination of sine functions and Perlin noise. The sine function creates the periodic up-and-down motion of waves, while the noise adds a bit of natural randomness, making the wave patterns look more organic as opposed to robotic.


The ocean on the canvas is made up of many layers of waves and wave shapes. Each layer represents a wave with different properties such as amplitude, wavelength, and speed, which are based on the selected sea state.


Each point along the wave's crest and trough is calculated based on the selected sea state and the current time elapsed since the program started, resulting in a smooth, cyclical movement.
