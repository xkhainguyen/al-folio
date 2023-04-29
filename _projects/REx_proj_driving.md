---
layout: page
title: driving MPC
description: trajectory optimization and model predictive control for autonomous driving
img: assets/rex_lab/drivingMPC.gif
importance: 1
category: lab
---

This is my previous project at the Robotic Exploration Lab at CMU. Some key points:

- Employed ALTRO, an augmented Lagrange iLQR algorithm, to solve constrained trajectory optimization problems for autonomous driving applications, using bicycle models.
- Investigated local planning and control frameworks, such as time-varying LQR and model predictive control (MPC) using OSQP, to ensure safe and efficient operation, while handling control limits and obstacles.
- Algorithms and 3D visualization are implemented in Julia.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/rex_lab/drivingMPC.gif" title="driving MPC" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Replan to avoid obstacles and reach the goal.
</div>