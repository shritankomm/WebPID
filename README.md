WebPID: 
Browser-based PID controller simulation. Adjust Kp, Ki, and Kd in real time and observe how each parameter affects system stability. Visualizes overshoot, oscillation, and steady-state correction with a live response graph. No dependencies, open and run.

About: 
WebPID is a single-page interactive simulation for visualizing PID (Proportional-Integral-Derivative) controller behavior in real time. The simulation renders a top-down car driving along a road and uses a PID control loop to correct lateral drift back toward the centerline setpoint. Users can adjust Kp, Ki, and Kd gain values via sliders and immediately observe how each parameter influences system response. A live graph tracks lateral offset against the setpoint over time, making behaviors like overshoot, oscillation, and steady-state error visually apparent. Two car sizes are available, each with different physical properties including mass, friction, and disturbance sensitivity, requiring different tuning to achieve stability.

Status: 
WebPID is currently a work in progress. The core simulation and graph are functional but the project is actively being developed. Planned improvements include additional disturbance modes, preset tuning examples, improved car physics, a more detailed road environment, and expanded hotlink documentation within the interface. Contributions and feedback are welcome.

Usage: 
Download or clone the repository and open WebPID.html in any modern browser. No installation, build tools, or dependencies required.
