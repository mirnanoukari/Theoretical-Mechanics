# Theoretical Mechanics Assignment 2

## Task Description

In this assignment, we are asked to conduct an experiment and develop a mathematical model for the yo-yo. In order to prove that our solution is correct, it is necessary to compare the simulation result and experimental results.

## Tools

- Python
- Camera
 

## Modeling

Research object is the yo-yo, which can be considered as a particle moving in a translation motion and rotational motion, consists of two disks (for approximation) and cylinder connection between the disks

Using the principle of conservation of energy

0.5 m v^2 + 0.5 I w^2 - mgL = 0


*I* is inertia around *x-axis* of rotation

v = L'(t) = w r_0

Substituting *v* in the equation we get

L'(t)^2 = 2 g L / 1 - (I / m r_0)

Solving the previous ODE, we obtain the [solution](https://www.wolframalpha.com/input/?i=x%28t%29+%27+%5E+2+%3D+2+g+x%28t%29+%2F+%281+-+i+%2F+%28m+r0%29%29&assumption=%22i%22+-%3E+%22Variable%22) of L.

## Experiments

### Table 1

Initial string length over the number of oscillations:

| # Experiment | String length | # Oscillations |
| ------------ | ------------- | -------------- |
| 1            | cm            |                |
| 2            | cm            |                |
| 3            | cm            |                |
| 4            | cm            |                |
| 5            | cm            |                |

### Table 2

Maximum distance from bottom position (oscillation amplitude) over oscillation:



| # Experiment | 1    | 2    | 3    | 4    | 5    | Mean | STD  |
| ------------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1            |      |      |      |      |      |      |      |
| 2            |      |      |      |      |      |      |      |
| 3            |      |      |      |      |      |      |      |
| 4            |      |      |      |      |      |      |      |
| 5            |      |      |      |      |      |      |      |

