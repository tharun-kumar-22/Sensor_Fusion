# Sensor Fusion - Kalman and Particle Filter

This repo contains implementations of Kalman Filter and Particle Filter for a ball throwing use case, provided in both Jupyter Notebook and HTML formats.

## Files:

1. `Task_P2.1(Kalman Filter).ipynb` - Source code implementation of the Kalman filter for the ball throwing use case in Jupyter Notebook format. 
2. `Task_P2.2(Particle Filter).ipynb` - Source code implementation of the Particle filter for the ball throwing use case in Jupyter Notebook format.
3. `Task_P2.1(Kalman Filter).html` - Source code implementation of the Kalman filter for the ball throwing use case in HTML format.
4. `Task_P2.2(Particle Filter).html` - Source code implementation of the Particle filter for the ball throwing use case in HTML format.

Download the ipynb files and run the code using jupyter notebook or visual studio or google colab.

## Prerequisites
1. Python should be installed in your system.
2. The following Python libraries should be installed:
   - Numpy
   - Matplotlib
   - Seaborn
   - Plotly
   - Scipy
   - FilterPy

You can install these libraries using pip(if not available): !pip install numpy matplotlib seaborn plotly scipy filterpy 


## Kalman Filter Implementation:

1. Plotted the trajectory of the ball along with horizontal and vertical velocities.
2. Implemented the ball throwing use case using the `kalman_filter` function from the `filter.py` standard python library to estimate the ball's position.
3. Developed a Kalman filter from scratch using equations provided in lecture slides to estimate the ball's position and velocity over distance.
4. Compared both and analyzed plots of the estimated positions to demonstrate the Kalman filter's performance.
5. Plotted estimated positions and velocities against real and observed (noisy) data using Plotly and Matplotlib.

## Particle Filter Implementation:

1. Plotted the trajectories and horizontal and vertical velocities of multiple balls.
2. Implemented all standard steps of the `particle filter` (initialization, prediction, update, resampling, etc.) for throwing two balls simultaneously.
3. Plotted estimated positions and velocities against real and observed (noisy) positions and velocities for two balls using Plotly and Matplotlib.

## Acknowledgement:

Thanks to Prof. Dr. Frank Deinzer for providing insightful lectures on Reasoning and Decision Making under Uncertainty.
