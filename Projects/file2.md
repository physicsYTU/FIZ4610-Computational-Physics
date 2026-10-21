Simple Hanging Harmonic Oscillator

In this set of exercises the student builds a computational model of a hanging mass-spring system that is constrained to move in 1D,
using the simple Euler and the Euler-Cromer numerical schemes. The student is guided to discover, by using the model to produce graphs
of the position, velocity, and energy of the mass as a function of time, that the Euler algorithm does not conserve energy, 
and that for this simple oscillatory system, a modified algorithm (Euler-Cromer) is necessary to avoid artificial behavior in the model.

Exercise 1: Euler Algorithm Model of a SHO

Build a computational model of a simple hanging harmonic oscillator using the Euler method. Use realistic values for the parameters (i.e., spring constant k and attached mass m, such as would be encountered in a typical introductory mechanics laboratory exercise. Also, assume that the mass of the spring is negligible compared to the attached mass, and that the harmonic oscillator has been stretched vertically downward a distance y0, relative to its hanging equilibrium position and released from rest. Use the model to produce graphs of the position and velocity of the mass as a function of time, and compare these with the exact functions for the position and velocity,

y(t)=y0cos(km−−−√t)(14)
and

v(t)=−km−−−√y0sin(km−−−√t),(15)

that result from solving Newton’s 2nd Law analytically. Does the angular frequency match that expected for a simple harmonic oscillator of mass m an spring constant k?

Exercise 2: Artificial Behavior with the Euler Algorithm

You may (should!) have noticed that something is not right with the Euler model of your hanging oscillator. Describe in detail the artificial behavior you observe in your model, and explain why it doesn’t represent a realistic oscillating mass. Recall that in the Euler method, the accuracy of the solution can be increased by using a smaller value of Δt. Can you get rid of the artificial behavior by making Δt smaller?

Exercise 3: Energy in the Euler Algorithm Model of a SHO

Modify your model to produce a graph of the total energy of the oscillator as a function of time. Describe in detail what happens to the energy, and the artificial behavior observed. Can this artificial behavior in the energy be corrected by making Δt smaller? What can you conclude about using the Euler method to model a simple harmonic oscillator?

Exercise 4: Euler-Cromer Algorithm Model of a SHO

Build a model of the hanging oscillator using the modified Euler, or Euler-Cromer, numerical method. Compare the results you obtain (i.e. position and velocity vs. time) with those obtained from the simple Euler method, and with the exact solution. Comment in detail on your results.

Exercise 5: Energy in the Euler-Cromer Algorithm Model of a SHO

Modify your model to produce a graph of the total energy as a function of time. Is energy conserved for the Euler-Cromer algorithm?
