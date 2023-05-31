---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## First-order Algorithm for Riemannian Online Optimization  

<img width="300" height="300" align="right" src="../images/profile.png"/>

We consider the online optimization on Riemannian manifolds in the full information setting, 
where a learner sequentially interacts with the environment by observing function values or gradients on a Riemannian manifold.
The goal is to minimize the regret of the learner, which measures the deviation of the learner's performance from the fixed optimal solution.   
 <img src="" align="right; width-20">
 
To address the problem, we introduce the Riemannian Online Gradient Descent (R-OGD) algorithm, where the exponetial map is utilized to present the gradient descent. Our algorithm delivers regret bounds of $\mathcal O(\sqrt{T})$ and $\mathcal O(\log T)$ for geodesically convex (g-convex) and strongly geodesically convex functions, respectively, on Hadamard manifolds. Additionally, we extend these bounds to manifolds with positive curvature by effectively addressing the challenges associated with non-constrictive projection maps. At last, we establish a universal lower regret bound of $\Omega(\sqrt{T})$ for g-convex functions in the worst case, demonstrating the optimality of the regret bound achieved by R-OGD.



