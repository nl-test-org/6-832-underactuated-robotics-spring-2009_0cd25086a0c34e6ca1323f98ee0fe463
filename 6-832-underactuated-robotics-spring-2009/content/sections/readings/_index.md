---
course_id: 6-832-underactuated-robotics-spring-2009
layout: course_section
menu:
  leftnav:
    identifier: d49b78fef56df97f9681953c45ae4447
    name: Readings
    weight: 30
title: Readings
type: course
uid: d49b78fef56df97f9681953c45ae4447

---

This section is divided into [recommended textbooks](#Recommended_Textbooks), [readings by session](#Readings_by_Session), and [course notes](#Course_Notes). There are no required textbooks for this course.

{{< anchor "Recommended_Textbooks" >}}{{< /anchor >}}Recommended Textbooks
--------------------------------------------------------------------------

A list of relevant textbooks is given below:

Strogatz, Steven H. _Nonlinear Dynamics and Chaos: With Applications to Physics, Biology, Chemistry, and Engineering_. Boulder, CO: Westview Press, 2001. ISBN: 9780738204536.

Slotine, Jean-Jacques E., and Weiping Li. _Applied Nonlinear Control_. Upper Saddle River, NJ: Prentice Hall, 1991. ISBN: 9780130408907.

Fantoni, Isabelle, and Rogelio Lozano. _Non-linear Control for Underactuated Mechanical Systems_. New York, NY: Springer-Verlag, 2002. ISBN: 9781852334239.

Bertsekas, Dimitri P. _Dynamic Programming and Optimal Control_. 3rd ed. Vols. I and II. Nashua, NH: Athena Scientific, 2007. ISBN: 9781886529083 (set).

[![Buy at MIT Press](/images/mp_logo.gif)](https://mitpress.mit.edu/9780262193986) Sutton, Richard S., and Andrew G. Barto. [_Reinforcement Learning: An Introduction_](https://mitpress.mit.edu/9780262193986). Cambridge, MA: MIT Press, 1998. ISBN: 9780262193986.

Bertsekas, Dimitri P., and John N. Tsitsiklis. _Neuro-Dynamic Programming_. Nashua, NH: Athena Scientific, 1996. ISBN: 9781886529106.

LaValle, Steven M. _Planning Algorithms_. New York, NY: Cambridge University Press, 2006. ISBN: 9780521862059.

{{< anchor "Readings_by_Session" >}}{{< /anchor >}}Readings by Session
----------------------------------------------------------------------

The readings below come from the course notes "Underactuated Robotics: Learning, Planning, and Control for Efficient and Agile Machines."

| SES # | TOPICS | READINGS |
| --- | --- | --- |
| 1 |  {{< br >}}{{< br >}} Fully- vs. under-actuated systems {{< br >}}{{< br >}} Preliminaries {{< br >}}{{< br >}}  | Chapter 1 and Appendix A |
| 2 | Nonlinear dynamics of the simple pendulum | Chapter 2 |
| 3 |  {{< br >}}{{< br >}} Introduction to optimal control {{< br >}}{{< br >}} Double-integrator examples {{< br >}}{{< br >}}  | Chapter 9 |
| 4 |  {{< br >}}{{< br >}} Double integrator (cont.) {{< br >}}{{< br >}} Quadratic regulator (Hamilton-Jacobi-Bellman (HJB) sufficiency), min-time control (Pontryagin) {{< br >}}{{< br >}}  | Chapter 10 |
| 5 | Dynamic programming and value interation: grid world, double integrator, and pendulum examples |  {{< br >}}{{< br >}} Chapter 9 (cont.) {{< br >}}{{< br >}}  |
| 6 | Acrobot and cart-pole: controllability, partial feedback linearization (PFL), and energy shaping | Chapter 3 |
| 7 | Acrobot and cart-pole (cont.) | Chapter 3 (cont.) |
| 8 | Policy search: open-loop optimal control, direct methods, and indirect methods | Chapter 12 |
| 9 | Policy search (cont.): trajectory stabilization, iterative linear quadratic regulator (iLQR), differential dynamic programming (DDP) | Chapter 12 (cont.) |
| 10 | Simple walking models: rimless wheel, compass gait, kneed compass gait | Chapter 5 |
| 11 | Feedback control for simple walking models | Chapter 5 (cont.) |
| 12 | Simple running models: spring-loaded inverted pendulum (SLIP), Raibert hoppers | Chapter 6 |
| 13 | Motion planning: Dijkstra's, A-star | Chapter 13 |
| 14 | Randomized motion planning: rapidly-exploring randomized trees and probabilistic road maps | Chapter 13 (cont.) |
| 15 | Feedback motion planning: planning with funnels, linear quadratic regulator (LQR) trees | Chapter 14 |
| 16 | Function approximation and system identification | Chapter 8 and Appendix B |
| 17 | Model systems with uncertainty: state distribution dynamics and state estimation | Chapter 8 (cont.) |
| 18 | Stochastic optimal control | Chapter 15 |
| 19 | Aircraft | Chapter 7 |
| 20 | Swimming and flapping flight | Chapter 7 (cont.) |
| 21 | Randomized policy gradient | Chapter 17 |
| 22 | Randomized policy gradient (cont.) | Chapter 17 (cont.) |
| 23 | Model-free value methods: temporal difference learning and Q-learning | Chapter 16 |
| 24 |  {{< br >}}{{< br >}} Actor-critic methods {{< br >}}{{< br >}} Final project presentations {{< br >}}{{< br >}}  | Chapter 18 |
| 25 | Final project presentations |   

{{< anchor "Course_Notes" >}}{{< /anchor >}}Course Notes
--------------------------------------------------------

Selected chapters from the course notes are available below. Updated revisions of the course notes are available [here](http://groups.csail.mit.edu/locomotion/pubs.html).

| CHAPTERS | TOPICS |
| --- | --- |
| Front | Title page, table of contents, and preface ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_preface)) |
| 1 | Fully actuated vs. underactuated systems ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch01)) |
| {{< td-colspan 2 >}}**I. Nonlinear dynamics and control**{{< /td-colspan >}} ||
| 2 | The simple pendulum ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch02)) |
| 3 | The acrobot and cart-pole ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch03)) |
| 4 | Manipulation |
| 5 | Walking ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch05)) |
| 6 | Running |
| 7 | Flight |
| 8 | Model systems with stochasticity |
| {{< td-colspan 2 >}}**II. Optimal control and motion planning**{{< /td-colspan >}} ||
| 9 | Dynamic programming ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch09)) |
| 10 | Analytical optimal control with the Hamilton-Jacobi-Bellman sufficiency theorem ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch10)) |
| 11 | Analytical optimal control with Pontryagin's minimum principle |
| 12 | Trajectory optimization ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch12)) |
| 13 | Feasible motion planning |
| 14 | Global policies from local policies |
| 15 | Stochastic optimal control |
| 16 | Model-free value methods |
| 17 | Model-free policy search ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_ch17)) |
| 18 | Actor-critic methods |
| {{< td-colspan 2 >}}**IV. Applications and extensions**{{< /td-colspan >}} ||
| 19 | Learning case studies and course wrap-up |
| Appendix |  {{< br >}}{{< br >}} A. Robotics preliminaries ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_appa)) {{< br >}}{{< br >}} B. Machine learning preliminaries {{< br >}}{{< br >}}  |
| Back | References ([PDF]({{< baseurl >}}/sections/readings/mit6_832s09_read_refs))