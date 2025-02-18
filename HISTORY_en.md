# Introduction to mechanics
## What is mechanics?
* Mechanics is a mathematical science that studies the motion of bodies under the influence of forces.
## History of mechanics
**Galileo Galilei** began the modern era of mechanics by using mathematics to describe the motion of bodies. His *Mechanics*, published in 1623, introduced the concept of force and described the constantly accelerated motion of objects near the surface of the Earth.

Sixty years later, **Isaac Newton** formulated his laws of motion, which he published in 1687 under the title *Philosophiae Naturalis Principles Mathematica*. In the third book, entitled *De mundi systemate* , Newton solved the greatest scientific problem of his time by using his law of universal gravitation to determine the motion of the planets. Newton introduced a mathematical approach to the analysis of physical phenomena and rejected hypotheses without experimental basis.

This approach led to the extensive development of Newtonian mechanics, culminating in the work of **Lenard Euler**, who systematically studied the three-dimensional motion of rigid bodies and formulated the equations of motion of a rigid body known as Euler's equations. **Joseph-Louis Lagrang ** also made a significant contribution to the development of mechanics, who formulated analytical mechanics based on the principles of the calculus of variations. Lagrangian mechanics provided an elegant and general approach to solving mechanical problems through Lagrangian equations of the second kind, which allow the description of the dynamics of systems without the need to explicitly consider the forces acting on individual particles. During this development, the concept of energy gradually took shape, culminating in the mid-19th century with the discovery of the principle of conservation of energy and its application to thermodynamics. Conservation principles, including the conservation of momentum, energy, and angular momentum, became key in classical mechanics.

Newtonian mechanics was further applied to systems composed of many particles, leading to the development of continuum mechanics and the theories of fluid mechanics, wave mechanics, and electromagnetism. The development of the wave theory of light raised questions about the existence of the aether, which were refuted by the Michelson -Morley experiment in 1887. Subsequently, **Albert Einstein**, in his special theory of relativity (1905), rethought the concepts of space and time, thereby resolving the contradictions between optics and Newtonian mechanics.

Further limitations of Newtonian mechanics emerged at the microscopic level. Statistical mechanics was developed to connect the microscopic properties of atoms and molecules with the macroscopic thermodynamic properties of materials. In the early 20th century, quantum mechanics provided a mathematical description of microscopic phenomena that fully corresponded to experimental observations.

In the 20th century, it became clear that Newton's law of gravity no longer accurately described the large-scale universe and was replaced by general relativity. Observations such as the accelerating expansion of the universe in the late 20th and early 21st centuries led to the introduction of new concepts such as dark energy, which again required a reassessment of fundamental physical concepts.

![ Personalities of mechanics](http://www.encyclopedie-environnement.org/app/uploads/2016/10/lois-dynamique_focus_fig1_frise-chronologique-histoire-lois-dynamique.png)
    
It is divided into several main areas:
## Mechanics division
- **Classical mechanics** – includes Newtonian mechanics, analytical mechanics ( Lagrangian and Hamiltonian ) and continuum mechanics.
- **Relativistic mechanics** – deals with the motion of bodies at speeds close to the speed of light (Einstein's theory of relativity).
- **Quantum mechanics** – describes the behavior of particles at the microscopic level, where classical mechanics fails.
- **Statistical mechanics** – connects the microscopic properties of particles with the macroscopic properties of systems.

Within the framework of a one-semester In the mechanics course , we will primarily cover classical mechanics with a subtle look into statistical mechanics in defining entropy. In mechanics, one progresses from elementary to advanced in four general ways:


1. **Number of spatial dimensions.**
- 1D mechanics is the simplest. All forces act in one direction, for example in the x-axis direction (or the opposite)2D or 3D geometry is not considered . Some people call this "scalar" mechanics because vectors have minimal use in 1D .
- Plane or 2D mechanics is next in order of difficulty. 2D mechanics is most emphasized in simple applications. Geometry is important, but not overly complex.
- 3D mechanics is the most difficult. The geometry of three dimensions is surprisingly more difficult than two dimensions.
    
2. **Movement complexity.**
- Statics, which assumes no motion (or more precisely, negligible acceleration), is the simplest
- Rectilinear motion is next in order of difficulty, assuming that all points move parallel to one given straight line, such as the *x* axis.
- Circular motion refers to systems where all points move in circles around a given point in a plane or, in 3D , around a given fixed axis.
- General motion, where points and objects can move in any way, is the most general and difficult.
    
3. **System complexity.** In approximate order of difficulty, the systems that can be studied in particle and rigid body mechanics may be as follows:
- One particle (point mass).
- Particle system.
- Rigid body.
- System of particles and rigid bodies.
    
4. **Type of interaction.** Parts of a system interact with each other through forces. In dynamics, some interactions are easier to deal with than others.
- Forces determined by positions and velocities. The simplest interactions are when the forces come from springs, dampers, and gravity. This means that the forces can be found directly if you know the positions and velocities of all the objects.
- Forces and accelerations are coupled. These are systems that have parts that interact with linkages, such as hinges and sliding joints. These "kinematic" linkages are used to describe mechanisms.

![ Mechanics Division](https://www.mdpi.com/applmech/applmech-01-00001/article_deploy/html/images/applmech-01-00001-g001.png)

# Previous knowledge
  
**Mathematics**: Students are assumed to have a basic knowledge of geometry, algebra, trigonometry, differentiation, and integration. Some of these topics will be briefly explained, but not as ab initio tutorials. We will show how to use the solution of algebraic and differential equations to solve problems in mechanics.
  
**Programming**: You need to know, or be learning, a computer language or software that can solve linear algebra problems
equations, numerically integrate simple ordinary differential equations, and make decent graphs. In our course, we will primarily use the Python programming language. If you are not familiar with this language, you can also use Matlab or Mathematica.
   

# What this course includes
  
**Note**: Course content may change during the semester.
 
The course content is as follows:

0. **Introduction**
- Definition of division and history of mechanics
- Scalar and vector calculus
   
 
1. **Mechanics of 1-degree aromaticity systems **
- Kinematics of linear motion, degrees of freedom, relationship between path, velocity, acceleration, physical interpretation of derivative and integral, free fall, vertical throw.
- Dynamics of motion, Newton's laws, law of conservation of momentum,
- Energy and its conservation, Lagrangian description of motion
- Passive forces - friction , inclined plane,
- Measurement of force, speed and acceleration

2. **Linear force system**

- Balance, relaxation, external and internal forces
- Method of section, displacement, deformation (relative and natural elongation), stress, t
- Tensile diagram, material characteristics,
- Dimensioning of a member, a member of constant strength,
- Strain energy, impact stress,
- Tension measurement

3. **Periodic motion**
- Motion of a mass point along a circle, oscillation of an oscillator, natural, damped and excited oscillations,
- Pendulum – physical and mathematical pendulum,
- Double pendulum, Lagrange -Euler equations

4. **Movement and deformation in the plane**
- Motion of a mass point in a plane, superposition of motions,
- Dynamic equations of motion for a mass point
- Motion of a body in a plane, translational and rotational effects of force, moment of force, lever, Varignin's theorem
- Position of the center of gravity, center of gravity and balance, center of gravity and energy
  
5. **Dynamics of motion in a plane**
- Moment of inertia, moment of momentum, Steiner's theorem,
- Equations of motion of a body in a plane, inertial forces, Coriolis force,
- Law of conservation of angular momentum
  
6. **Planar stress state**
- Torsion and shear loads
- Stress and strain tensor, principal stress and principal strain, generalized Hooke's law
- Mohr's circle
- Membrane stress state, Laplace equation
- Strain gauge rose

7. **Beam and its load**
- Geometric characteristics of the cross-section, definition of the neutral axis,
- Beam sizing
- Strut

8. **Movement and deformation in space**
- Movement in three dimensions, balance in three dimensions
- Vector and matrix notation of equilibrium equations and equations of motion

9. **Mechanics of mechanisms**
- Transformation matrix for describing position and motion
- Simple mechanism and its analysis

10. **Spatial tension**
- Principal stresses and strains
- Reduced tension in 3D
- Combined stress – bending-bending, bending-compression, bending-torsion.

11. **Hydromechanics**
- Fluid and gas mechanics, hydrostatic paradox,
- Laminar and turbulent flow, Reynolds number, flow and continuity equation,
- Ideal and real liquid and its description.
- Ideal and real gas, gas equation of state

12. **Laws of Thermodynamics**
- Definition of entropy based on statistical mechanics
- Carnot cycle
- Heat engines, efficiency
# What this course does not include
  
**Relativity:** For physicists, classical mechanics also includes the special and general theories of relativity. To physicists, the word "classical" means "deterministic" or "non-quantum," so relativity, even though it came hundreds of years after Newton, is still called classical. Here, however, classical mechanics means mechanics as Newton and Euler understood it. Relativity is not discussed here.
 
**Theory of Bending and Torsion:** During the semester, we will learn to determine the course of bending moments, but we will not discuss the relationship between curvature and moment in beams or Mohr's integral.

**Engineering thermodynamics and hydrodynamics** is described only very simply without giving precise engineering descriptions and applications.

# Recommended reading
**Note**: The list of references will be updated throughout the semester.
    
- [ Classical Mechanics]( https://ocw.mit.edu/courses/8-01sc-classical-mechanics-fall-2016/pages/online-textbook/), online textbook of mechanics, MIT
- [Andy Ruina and Rudra Pratap : Introduction to Statics and Dynamics]( http://ruina.tam.cornell.edu/ Book /index.html), a freely available textbook with elaborate examples
- [Benjamin Crowel : Mechanics ]( https://www.lightandmatter.com/ mechanics /) a review of high school mechanics with subtle extensions.


