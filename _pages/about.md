---
permalink: /
title: "Ahlan! (Hello in Arabic)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello visitor, this is Mohammad Ramadan, PhD in Mechanical and Aerospace Engineering. In particular, I’m a control theorist with experience in stochastic optimal control, optimal filtering, and system identification.

I'm currently in Naperville (Chicago Western Suburbs), IL, working with the Mathematics and Computer Science Division, Argonne National Laboratory. These are my [Github](https://github.com/msramada), my [google scholar](https://scholar.google.com/citations?user=h7pE-VcAAAAJ&hl=en) and [LinkedIn](https://www.linkedin.com/in/msramada1/). Let's connect!

A little about me (outside research):
I'm into music, theory and production, and all sorts of movements: working out, yoga, calisthenics, wrestling and Brazillian jiu jitsu.

## Recent research projects:

### Data-Conforming Data-Driven Control

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <span style="font-size: 0.9em;">
      Data-driven and adaptive control approaches face the problem of introducing sudden distributional shifts beyond the distribution of data encountered during learning. Therefore, they are prone to invalidating the very assumptions used in their own construction. This is due to the linearity of the underlying system, inherently assumed and formulated in most data-driven control approaches, which may falsely generalize the behavior of the system beyond the behavior experienced in the data. This paper seeks to mitigate these problems by enforcing consistency of the newly designed closed-loop systems with data and slowing down any distributional shifts in the joint state-input space. This is achieved through incorporating affine regularization terms and linear matrix inequality constraints to data-driven approaches, resulting in convex semi-definite programs that can be efficiently solved by standard software packages. We discuss the optimality conditions of these programs and then conclude the paper with a numerical example that further highlights the problem of premature generalization beyond data and shows the effectiveness of our proposed approaches in enhancing the safety of data-driven control methods.
    </span>
  </div>
  <div style="flex: 1; margin-left: 20px;">
    <embed src="/files/Projects/DataConforming.pdf" width="320" height="360" type="application/pdf">
  </div>
</div>
<div style="margin-top: 20px;">
  <a href="https://arxiv.org/abs/2409.11549">Read the full paper here</a>
</div>

### Dampening parameter distributional shifts under robust control and gain scheduling

<div style="display: flex; flex-direction: column; align-items: center;">
  <div style="flex: 1; margin-bottom: 20px;">
    <iframe src="/files/Projects/distShifts.pdf" width="600" height="240"></iframe>
  </div>
  <div style="flex: 1;">
    <span style="font-size: 0.9em;">
      Many traditional robust control approaches assume linearity of the system and independence between the system state-input and the parameters of its approximant low-order model. This assumption implies that robust control design introduces no distributional shifts in the parameters of this low-order model. This is generally not true when the underlying actual system is nonlinear, which admits typically state-input coupling with the parameters of the approximating model. Therefore, a robust controller has to be robust under the parameter distribution that will be experienced in the future data, after applying this control, not the parameter distribution seen in the learning data or assumed in the design. In this paper we seek a solution to this problem by restricting the newly designed closed-loop system to be consistent with the learning data and slowing down any distributional shifts in the state-input and parameter spaces. In computational terms, these objectives are formulated as convex semi-definite programs that standard software packages can efficiently solve. We evaluate the proposed approaches on a simple yet telling gain-scheduling problem, which can be equivalently posed as a robust control problem.
    </span>
  </div>
  <div style="flex: 1; margin-top: 20px;">
    <a href="https://arxiv.org/abs/2411.16566">Read the full paper here</a>
  </div>
</div>

