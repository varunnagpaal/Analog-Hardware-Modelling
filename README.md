# Hands On Design, Modelling, Simulation(SPICE) and Prototyping of Discrete & Integrated Analog Circuits
This work involves hands-on design, modelling,  simulation and analysis (SPICE - MultiSim) of Discrete & Integrated Analog Circuits. Kind of activities involved in this work include:
- Understanding device structure and operating characteristics.
- Learn Circuit design modelling and analysis theory.
- Design and analyze circuits using pen-paper.
- Model and analyze circuits using simulation software (SPICE).
- Whenever possible, build circuits using real parts sourced from various vendors. Make measurement using real instruments and compare them with simulation results.

This is an ongoing work.

### Following is the bill of materials(BOM) of the list of parts used in various labs
- [LAOE-PE-PartsList.xlsx](https://github.com/varunnagpaal/Analog-Design-Modelling/blob/master/Parts/LAOE-PE-PartsList.xlsx)

The part numbers in the above BOM List above corresponds to Mouser specific part numbers. You may order parts from your country specific vendors(see Octopart BOM Tool)

### Notes
I do write lot of notes in notebook or on whiteboards. However, after a while I realized that sharing them becomes cumbersome and impractical.  So I decided to digitize my notes (not all though). Instead of pen & paper, I now write all my notes using Microsoft OneNote and XP-Pen Star 05 writing tablet . Below is link to my Microsoft OneNote on Analog circuits:
- [Analog Circuits Notes](https://1drv.ms/u/s!Ap5gga5jFlukggoewL7QWurL2oug)

### Following are the Analog Circuit topics which are dealt in this work. As I make progress, I expand the list of topics accordingly.
- [x] Measurement and Analysis
    - [x] Oscilloscope
        - [x] Transient response
        - [x] Frequency sweep
        - [x] AM/FM Modulation
    - [x] Spectrum Analyzer
        - [x] Bode Plots (Magnitude and Phase Frequency response)
        - [x] FFT
    - [ ] Network Analyzer
    - [ ] SPICE Analysis
        - [x] DC Operating (bias) point analysis (steady state)
        - [x] AC Analysis (Linearized Analysis) (Magnitude and Phase Frequency response or small signal response)
        - [x] DC Analysis or DC Sweep Analysis
        - [x] Parameter Sweep Analysis
        - [ ] Transient Analysis (dicretized time domain analysis)
        - [ ] Pole Zero Analysis
        - [ ] Fourier Analysis
        - [ ] Monte carlo analysis
        - [ ] DC and AC Sensitivity Analysis
        - [ ] Worst case analysis
        - [ ] Transfer function analysis
        - [ ] Noise Analysis
        - [ ] Distortion Analysis
        - [ ] Temperature Analysis
        - [ ] RF Analysis
        - [ ] User defined analysis
- [ ] Passive Devices and Circuits
    - [ ] Linear Devices
        - [x] Resistive: Resistance ('R')
        - [x] Reactive(X): Inductance('L'), Capacitance('C')
        - [x] Impedance ('Z')
        - [x] Switches
        - [ ] Relays
        - [ ] Connectors
        - [ ] LEDS and Displays
        - [ ] Variable Devices: R, L, C, Transformers
        - [x] Inductors and Transformers
    - [ ] Linear Circuit Analysis
        - [x] Voltage, current and Instantaneous Power
        - [x] Passive Sign Convention
        - [x] Power absorption or dissipation vs Power generation
        - [x] Linear static resistance and dynamic resistance
        - [x] Conductance and power dissipation in linear resistor and fixed/variable resistance
        - [x] Open circuit and short circuit
        - [x] Ideal Switch
        - [x] Independent and dependent power sources
        - [x] Ideal and practical power sources
        - [x] Reference voltage or ground
        - [x] Concept of grounding power supply and load
            - [x] Mains, Neutral  and Earth ground
            - [x] Floating (common) vs Earth Grounded returns
            - [x] Analog and digital grounds
        - [x] Circuit nodes and loops
        - [x] Lumped parameter approach to circuit analysis
        - [x] KCL and KVL
        - [x] Equivalent circuits
            - [x] Resistance in series and parallel
            - [x] Dominating resistance in series and parallel
            - [x] Source transformation
            - [x] Combining sources (series, split or differential)
        - [x] Voltage and Current division
        - [x] Bleeder resistance in voltage dividers
        - [x] Circuit reduction (ladder circuits)
        - [x] Nodal voltage and Mesh current Analysis
        - [x] Properties (homogeneity and superposition) of Linear circuits
        - [x] Input and Output Impedance (Thevenin and Norton equivalent circuits)
            - [x] Proportionality property
            - [x] Unit output method
            - [x] Measuring open circuit voltage, short circuit current and thevenin (lookback) resistance with instruments
            - [x] Application to non-linear loads
        - [x] Voltage, current or power interpreted as Signals
        - [x] Loading effect
            - [x] Effect of output impedance of source circuit on voltage signal attenuation (drooping) when loaded
            - [x] Effect of input impedance of measuring device on output voltage measurement
            - [x] Ideal source and load impedance
            - [x] Ideal and practical voltage and current measurement
            - [x] Thumb rules to minimize signal attenuation due to loading when cascading circuits
        - [x] Interface Circuit Design for given source/load constraints of voltage, current, impedance, power
            - [x] Maximum Signal (power) Transfer
            - [x] Impedance Matching
            - [x] Pass through, Series, Parallel
            - [x] L-pads, Bridge-T (Attenuation pad), O-pad
        - [x] Signals
            - [x] Basic time-varying signals
                - [x] Step and Unit step signal
                - [x] Representing finite duration signals in terms of unit step signal
                - [x] Ramp and unit ramp signal
                - [x] Impulse and Unit impulse signal
                - [x] Pulse (rectangular) and Unit pulse signal
                - [x] Gaussian (sinc) signal
                - [x] Squared sinc pulse signal
                - [x] Triangular and Unit triangular signal
                - [x] Exponential signal
                - [x] Sinusoidal signal
                    - [x] Amplitude, phase, frequency
                    - [x] Tone (fundamental), Harmonics and Multi-tone signals
                    - [x] Complex exponential
            - [x] Signal operations
                - [x] Scaling or Signal Gain
                - [x] Addition, Multiplication
                - [x] Shifting Left  (advance or leading) and right (delay or lagging) in time domain
                - [x] Time scaling
                    - [x] Compressing signal (scaling up frequency)
                    - [x] Expanding signal (scaling down frequency)
                    - [x] Time reversal
                - [x] Sampling and sifting property of Impulse signal
                - [x] Frequency shifting (modulation)
                - [x] Time windowing
                - [x] Differentiating (slope) and integrating (area) signals
                - [x] Relation between unit impulse, unit step and ramp function
            - [x] Signal characteristics
                - [x] Periodic vs Aperiodic
                - [x] Period of a multi-tone signal
                - [x] Phase
                - [x] Duty cycle of periodic signal
                - [x] Causality of a signal
                - [x] Amplitude vs magnitude
                - [x] Peak value and peak to peak value
                - [x] Real vs Complex signal
                - [x] Dimension of support
                - [x] Deterministic vs Random signals
                - [x] Even vs Odd signals
                - [x] Symmetry
                    - [x] Even and odd symmetry for real valued signals
                    - [x] Conjugate symmetry and asymmetry for complex signal
                    - [x] Decomposing real valued signal into even and odd parts
                    - [x] Decomposing complex valued signal into conjugate symmetric and asymmetric components
                - [x] Energy and power of a signal
                - [x] Time averaging operator
                - [x] RMS value of a signal
                - [x] Energy and power signals
        - [x] Basic AC Concepts
            - [x] Sinusoidal frequency, phase, amplitude
            - [x] Fundamentals and harmonics
            - [x] Instantaneous, RMS, Average values
            - [x] Frequency dependent Impedance of energy storing passive linear devices (L, C)
            - [x] Phasors
            - [x] Capacitor
                - [x] Static and dynamic description
                - [x] Blocking or Coupling and Bypassing or Decoupling capacitor
                - [x] Distortion effects of capacitor to non-sinusoidal time varying signals
                - [x] Electrolytic capacitors
            - [x] Gain/Attenuation, dB scale(octave/decade), Cascade gains
            - [x] Magnitude and Phase Frequency response (Bode Plots)
            - [x] Fourier Series(periodic), Fourier Transforms(aperiodic) and Laplace Transforms
            - [x] Transfer function (s-domain/z-domain), Pole-Zero plots
            - [ ] Domain transformations (time-domain to s-domain to z-domain)
            - [x] First and second order AC circuits R, L, C
                - [x] Transient (natural and step) response
                - [x] Steady state response
    - [ ] Non-linear devices
        - [x] Diodes
            - [x] Basic operating modes: forward biased, reverse biased and breakdown
            - [x] Effect of temperature on knee voltae and reverse biased current
            - [ ] Forward biased operation model
                - [x] Non-linear Exponential or Shockley model for small-signal didoes
                    - [x] Analytical solutions based upon Node voltage method
                        - [x] Iterative solution
                        - [x] With  diode as a non-linear load, replacing linear source circuit with Thevenin equivalent
                    - [x] Graphical solution
                        - [x] Load-line method
                - [x] Constant forward voltage drop model
                - [x] Ideal diode model (voltage controlled ideal switch)
                - [ ] Piece-wise linear diode models
                - [ ] Linear Small signal model (a linear resistance) of a diode
            - [x] Reverse biased operation models
            - [ ] Applications of diode
                - [x] Clipper or Limiter
                - [x] Thresholders
                - [x] Half wave rectifier
                - [x] Full wave bridge rectifier
                - [ ] Full wave bridge rectifier with smoothing capacitor
                - [ ] Photodiodes
                - [ ] Solar (PV) cells
                - [ ] Peak detector
                - [ ] Level restorers
                - [ ] Voltage doubler
                - [ ] Superdiode
        - [ ] Memristor
            - [ ] To be continued...
- [x] Modeling circuits as multi-port networks
    - [x] 2-port networks
        - [x] T and Pi-networks
        - [x] Symmetrical and Reciprocal Networks
        - [ ] Network Analysis
            - [x] Basics
                - [x] Types of 2-port parameters
                    - [x] [z] or open circuit impedance paramater
                    - [x] [y] or short circuit admittance parameter
                    - [x] finding [z], [y] for networks with and without dependent sources
                    - [x] hybrid [h] and inverse hybrid [g] parameters
                    - [x] chain or transmission [T] or ABCD parameters
                - [x] Interrelationshiop between different 2-port parameters
                - [x] Interconnecting 2-port networks
                    - [x] Parallel interconnection of 2-port networks
                    - [x] Series connection of 2-port networks
                    - [x] Cascade connection of 2-port networks
                    - [x] Series-Parallel connection
            - [x] Objectives of 2-port network analysis
            - [x] Need for 2-port analysis
            - [ ] To be continued..
- [ ] Linear Active Device based Circuits
    - [x] Passive devices vs Active Devices
    - [x] Active device and circuits
    - [x] Linear dependent sources
        - [x] CCCS, CCVS, VCVS, VCCS
        - [x] Gain: current gain, trans-resistance, voltage gain, trans-conductance
        - [x] linear dependent sources as used for modeling active devices
    - [x] Basic amplification concepts
        - [x] Voltage/Current/Power gain of Amplifier for DC/AC signals
        - [x] 2-port models of Ideal Voltage(VCVS) and Current(CCCS) Amplifiers
    - [ ] Real OpAmp vs Ideal OpAmp(VCVS) model
        - [x] Terminals: Power supply, Double ended differential inputs, Sngle ended output
        - [x] Differential amplifier characteristsics (Open loop gain, I/O Impedance)
        - [x] Voltage constraints on I/O terminals
        - [x] Operation modes (linear, saturation)
        - [x] Negative feedback (virtual short)
        - [x] Closed loop gain parameters
        - [x] Circuit analysis of OpAmp based Negative feedback circuits
        - [x] Open loop vs Closed loop gain
        - [x] Impedance and Loading effects on gain
        - [ ] Noise gain, Gain-Bandwidth Product, Phase Margin
    - [x] OpAmp based Voltage Amplifier Active circuits in Negative feedback configuration
        - [x] Gain inversion based on biased input terminal
        - [x] Inverting Amplifier (virtual ground)
        - [x] Non-inverting Amplifier
        - [x] Voltage follower or Non-inverting Buffer (virtual ground)
        - [x] Difference (subtracting) Amplifier
        - [x] Inverting Summing (Adder) Amplifier
        - [x] Non-inverting Summer (Averager) Amplifier
        - [x] Differentiating Amplifier (Inverting type, stability)
        - [x] Integrator Amplifier (Inverting type)
        - [x] Negative resistor converter
        - [x] Comparators
    - [ ] OpAmp Applications
        - [x] see Active Filters (R, C, OpAmp based)
        - [ ]  To be continued..
    - [ ] Negative feedback concepts
        - [x] Open vs Closed loop gain
        - [x] Gain desensitivity and Error
        - [x] Linearizing effect
        - [x] Effects on noise and distrubances
        - [ ] To be continued...
- [ ] Analog Filters
    - [ ] Basic Filter Concepts
        - [x] Types: Low Pass(Baseband), High Pass, Bandpass, Bandstop(Notch), All Pass
        - [x] Magnitude/Phase Frequency response (Bode Plots)
        - [ ] Passband/Stopband/Transition-band Characteristics and Approximations
            - [x] Cut-off(-3 dB), Stopband edge and Center Frequency
            - [x] Closed loop Gain (DC, PassBand, Stopband)
            - [x] Monotonocity (Ripple, Flatness)
            - [x] Roll-off slope (attenuation rate in transition band)
            - [x] Total Harmonic Distortion
            - [x] Reasonance, Q-factor(Sharpness), Frequency selectivity, Tunability
            - [x] Filter order and its effect on roll-off
            - [x] Bandwidth
            - [x] Transient response, Impulse/step response
            - [x] Filter loading effects: Source side output and Load side input impedance
            - [X] Phase and Group Delay
            - [ ] Causality and Stability analysis
            - [ ] Filter transformations
    - [ ] Filter circuits
        - [x] Passive Filters (R, L and C based)
        - [ ] Active Filters (R, C, OpAmp based)
            - [x] Basic first order Active filters (LP/HP)
            - [x] Cascade design of higher order active filters using 1st order active filters
            - [x] Butterworth (maximally flat)
            - [x] Chebyshev type I (equiripple) and II (inverse)
            - [x] Elliptical or Cauer
            - [x] Bessel
            - [x] Sallen Key filter (2nd order LP, HP, BP, Notch)
            - [ ] To be continued..
        - [ ] Switched Capacitor Filters
        - [ ] FIR and IIR Filters
    - [ ] Filter Applications
        - [ ] Anti-aliasing, Smoothing(reconstruction), Noise filtering
        - [ ] Radio(FM/AM), TV, Telephone(FDM), Communication, Audio(Equalization)
- [ ] Analog Integrated Circuits
    - [ ] Active devices and circuits
        - [ ] Bipolar Junction Transistors(BJT)
            - [x] Large signal and small signal models
            - [ ] As a Switch
            - [ ] As an Amplifier
        - [ ] Field Effect Transistors (FET)
            - [x] JFET (Junction Field Effect Transistors)
            - [ ] CMOS FET (Metal Oxide Semiconductor FET)
                - [x] Device structure and I/V Characteristics
                - [x] Large signal and small signal models
                - [ ] Short Channel Effects
                - [ ] Transitioning from CMOS FET to FinFET
                - [x] As a Switch
                - [ ] As an Amplifier
                    - [ ] Single stage Amplifier
                    - [ ] Differential Amplifier
                    - [ ] Current Mirrors and Biasing
                    - [ ] Noise
                    - [ ] Non-linearity and Mismatch
                    - [ ] Feedback
                    - [ ] Operation Amplifiers
                    - [ ] Stability and Frequency Compensation
                    - [ ] Bandgap references
                - [ ] Switched Capacitor Circuits
                - [ ] Timing and Synchronization Circuits
                    - [ ] Oscillators (VCO) and timers
                - [ ] Frequency Synthesis
                    - [ ] Phase Locked Loops (PLL)
                        - [ ] Frequency multiplication and synthesis
                        - [ ] Clock generation and clock recovery
                        - [ ] Tone decoding and demodulation
- [ ] Mixed Signal Circuits
    - [ ] Digital to Analog Converters (DAC)
    - [ ] Analog to Digital Converters (ADC)
        - [ ] Parallel Flash
        - [ ] Successive Approximation (SAR)
        - [ ] Integrating
        - [ ] Delta-Sigma

### Following references serve as rough guide for this work
* *Signal Measurement and Analysis*
    * [XYZs of Oscilloscopes](http://info.tek.com/in-xyzs-of-oscilloscopes-primer.html) by Tektronix
    * [Logic Analyzer Fundamentals](http://info.tek.com/www-logic-analyzer-fundamentals.html) by Tektronix
* *Linear Circuit Analysis and Design*
    * [The Analysis and Design of Linear Circuits](http://amzn.in/gmD5WMM) by Roland E. Thomas, Albert J. Rosa, Gregory J. Toussaint-Wiley
    * [Electrical Engineering Principles and Applications](http://amzn.in/iPsHjZ3) by Allan R. Hambley
    * [Basic Linear Design](http://www.analog.com/en/education/education-library/linear-circuit-design-handbook.html) by Analog Devices 
    * "[Basic Electrical Circuits](https://www.youtube.com/watch?v=TNCyIw9JC6k&list=PLYGynSK2bDIdjS66YGVhdczcialGVKtBG)" lectures by Nagendra Krishnapura, Dept. of EE, IIT Madras
    * "[Real Analog - Circuits 1](https://learn.digilentinc.com/classroom/realanalog/)" lectures by Digilent
* *Active Circuits*
    * [TI - Op Amps for Everyone](http://web.mit.edu/6.101/www/reference/op_amps_everyone.pdf) by Ron Mancini
    * [Design With Operational Amplifiers and Analog Integrated Circuits](http://amzn.in/5FjDISx) by Sergio Franco
* *Analog Filters*
    * [A Basic Introduction to Filters — Active, Passive, and Switched-Capacitor](http://www.ti.com/lit/an/snoa224a/snoa224a.pdf) by Kerry Lacanette
    * [Analog Filter Design](http://amzn.in/d414kcy) by Rolf Schaumann
* *Microelectronics*
    * [Microelectronic Circuits: Theory And Applications](http://amzn.in/aeyBLhA) by Adel S. Sedra, Kenneth C. Smith
* *Analog Integrated Circuits*
    * [Design of Analog CMOS Integrated Circuits](http://amzn.in/hZJ8iav) by Behzad Razavi
* *References*
    * [TI Analog Engineer's Pocket Reference](http://www.ti.com/lit/slyw038) by Art Kay and Tim Green
    * [Learning the Art of Electronics(LAOE)](http://learningtheartofelectronics.com/) by Thomas C. Hayes and Paul Horowitz
    * [Practicing Electronics For Inventors(PEFI)](https://accessengineeringlibrary.com/browse/practical-electronics-for-inventors-fourth-edition) by Paul Scherz, Dr. Simon Monk 
