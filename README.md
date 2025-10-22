# AcceleratorDictionary
a brief and non comprehensive dictionary of accelerator physics jargon, if you wish to help contribute to the effort contact me @ phia@stanford.edu 

https://uspas.fnal.gov/resources/AcceleratorTerms.pdf 

Types of accelerators:
Linear accelerator/LINAC - any accelerating structure that gives a beam of particles energy that is primarily linear, ie the acceleration is done in a straight line. The acceleration is often done with RF cavities. 

Synchrotron/circular accelerator - accelerates particles around a circular closed orbit and the particles usually go around the loop many times to reuse the accelerating structure. This orbit is maintained with magnets that bend the particles, with increasing force as the particles reach higher energies. The limit to the energy they can reach usually comes from synchrotron radiation, which causes particles to lose energy as they bend. 

Cyclotron- a structure that uses a large magnet to bend particles and a small accelerating gap (voltage difference) to accelerate particles. As the particles gain more energy they travel in larger circles around the magnet, until they are spit out at a fixed radius and known energy at the edge of the magnet. Compared to a synchrotron, here the particles travel in a spiral rather than a fixed orbit.
http://www.geology.wisc.edu/~johnf/g777/Misc/chap15.pdf
https://cas.web.cern.ch/sites/default/files/lectures/erice-2017/tecker.pdf

Relating to accelerator components
Radiofrequency/RF
A specific frequency of electromagnetic radiation ranging from ~3kHz to ~300GHz. It describes the rate of oscillation for an alternating current, voltage, electric field, or magnetic field in that frequency range. An example: Electric currents that oscillate at radiofrequency are called RF currents.

RF cavity 
An RF cavity is a component that uses electromagnetic fields to transfer energy to a beam of particles within an accelerator. It is a chamber with an aperture that a beam of particles passes through, resulting in acceleration or deceleration of the particles. 

How RF cavities have an electromagnetic field:
RF cavities are each powered by something called a klystron. The electromagnetic waves
How RF cavities accelerate the beam:
The RF cavities contain an electromagnetic field, and the particles that go through this field are then accelerated/decelerated depending on when they arrive at the cavity. This is because the electromagnetic field in an RF cavity is oscillating at radiofrequency, and the particles must arrive at an optimal phase of the electromagnetic wave to be accelerated.
		
Undulator
A series of dipoles (North-South magnets) alternating to wiggle the particles. This is also sometimes called a wiggler. This is the basis for free electron lasers (FELs), which wiggle the beam. When the particles in the beam accelerate (wiggle) they emit synchrotron radiation, usually in the X-ray regime for FELs.

Klystron
A klystron is a source of RF power for accelerators. An electron beam is emitted by the klystron’s cathode, then accelerated by a voltage. 

Electron gun
Where the electrons come from. This could be a photocathode, which is a chunk of metal whose electrons are liberated when hit with a laser or it could be a thermionic gun, which releases electrons when it is heated. 

Quadropoles
These are magnets that focus in one direction and defocus in another direction. This is because the strength of the magnetic field is highest closest to the magnets (furthest from the center). Therefore, the particles furthest from the beamline are deflected and focused more. These are usually used in a lattice to achieve an overall focusing effect. These lattices are called FODO (focusing-defocusing), FOFO, FODOFO, etc… The transport of a beam through a lattice can be described by a series of matrices, usually denoted M. 

Dipoles
These magnets bend the beam via the Lorentz force (which is what governs almost all of accelerator physics). A particle moving in a magnetic field that is not parallel with the particle's motion will be bent. A faster particle is more “rigid” and bends less than a slower particle. This can be used to measure the particles energy or tp bunch the beam in a chicane. 

Chicane
A chicane is a series of dipoles (usually 4) that take advantage of the difference in bending between fast and slow particles to bunch the beam. https://www.hzdr.de/db/Cms?pOid=12098&pNid=584&pLang=en

Vacuum
An area in which the pressure is extremely low. Perfect vacuum, which is not achievable due to quantum fluctuations, would be the absence of any particles. 

Bunching
Compressing the beam in position space, usually by elongating the beam in momentum space (since emittance is compressed). This is often done with a chicane. 

Gamma factor
A factor that is used to describe relativistic effects, also called the Lorentz factor. The gamma factor depends on the speed of the object, and can be used to convert to energy of a particle in MeV using the rest energy of the particle. In the case of a proton, the rest energy is 938 MeV. We can convert the gamma factor to MeV using (rest energy)*(gamma factor).

Other:
Superconducting- usually in the context of the accelerating cavities. The cavities are made of superconducting material and therefore have a higher conductivity. 

Accelerating gradient- The achievable energy gain of a particle in an accelerator per unit length. Higher gradients mean you can reach higher energy in a shorter space. 
Shunt impedance- defines the relationship between RF power supplied and the accelerating voltage achieved. 
https://accelconf.web.cern.ch/l06/papers/TUP044.pdf

Cryogenic- cold temperatures, 77 K for liquid nitrogen and 4 K for liquid He.

Plastic deformation- a distortion in a material that exceeds the material’s yield strength. This deformation cannot be reversed. The other type of deformation is elastic deformation, which cannot be reversed. Plastic deformation can occur in cavity walls when a breakdown deposits too much heat, which can impact the cavity performance by changing its shape. https://journals.aps.org/prab/pdf/10.1103/PhysRevAccelBeams.23.072001
TME=theoretical minimum emittance

Relating to things that happen to the beam
Emittance (ε)- the size of the beam in phase space (position and momentum coordinates). This is defined as the area of the beam in position and momentum (along x,y axes, transverse emittance) or energy and momentum spread coordinates (along z axis*, longitudinal emittance). Low emittance beams are smaller, but harder to make. For most processes normalized emittance is conserved (Louiville’s theorem). To decrease emittance damping rings (for electrons at least) are often used. 

Normalized emittance (εɣβ)- Emittance will change as a function of the energy of the beam thanks to special relativity (length contraction). Normalized emittance is what is conserved, which is emittance times gamma (the relativistic factor) and beta (the particle’s velocity as a fraction of c). 

RF breakdown- when a RF cavity is filled with a high electric field, small imperfections on the surface can cause charge to collect and then arc to the other side of the cavity to discharge. This can leave small burn marks and degrade the cavity performance over time. 

Iris aperture- size of the diameter of the ‘iris,’ which is another way of saying a beamline component that is a physical barrier to the stray particles that are not at the center of the beam. 
Beam spread- literally spread in the size of the beam 

Bragg peak- heavy ions in material deposit energy in matter by ionizing the atoms in the material according to the Bethe-Bloch formula. They lose energy quicker at lower energies and therefore deposit more of their energy at the end of their path. The curve of energy deposition is the Bragg curve, which has a characteristic Bragg peak at the end of the particle’s path. Spend some time to understand this

Energy modulation- “modulating,” or changing the energy of the particles in the beam
Bunches- literal bunches/groups of particles that clump together. In collider experiments these are often in a ‘bunch train’ which is a series of many bunches. 

Twiss parameters- the beam is described by an ellipse in phase space (position and momentum). The Twiss parameters 𝛼, β, 𝛾 describe the geometry of the ellipse. Note, the 𝛾 here is not the relativistic factor describing the speed of the beam.

*The z axis is typically defined as along the direction the beam is travelling and particle position is given in relation to a “reference particle” at the center. 

Medical accelerators specifically: 
Pencil beam scanning
Method used in proton therapy to more precisely scan tumors layer by layer, and shaping the treatment area. The beam can be manipulated such that a pattern of protons can be created, allowing the beam to treat irregularly shaped tumors or around organs.

Energy degrader- I think that this is the traditional energy modulation technique in proton therapy, in which a beam is created at fixed energy and absorbing material is place between the end of the accelerator and the patient to reduce and tune the energy of the beam. 
