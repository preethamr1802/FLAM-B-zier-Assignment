Title: Interactive Bézier Rope Simulation
How to run: Open bezier_rope.html in a browser.
Description: Implements a cubic Bézier curve reacting to mouse movement using spring-damping physics.
Math: B(t) = (1–t)^3P0 + 3(1–t)^2tP1 + 3(1–t)t^2P2 + t^3P3
Physics: acceleration = –k*(position–target) – c*velocity
Integration: Semi-implicit Euler
Parameters: k = 400, c = 40
Controls: Move mouse or drag colored points.
