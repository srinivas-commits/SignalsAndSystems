Signals And Systems
=================

******
To add pictures to the link :

Website for picture, https://img.youtube.com/vi/[---------]/maxresdefault.jpg

For the above link, replace [---------] with youtube link code<br>
Code for this youtube link, https://www.youtube.com/watch?v=FhVQjuAtlTs, code is: FhVQjuAtlTs

<a href="https://github.com/zzossig/hugo-theme-zzo/issues/88" target="_blank">external link</a>

Ex:

[![Watch the video](https://img.youtube.com/vi/4PUcOf0koxw/maxresdefault.jpg)](https://youtu.be/4PUcOf0koxw)

****

Table of contents
=================

<!--ts-->
   * [Signals and systems](#signals-and-systems)
   * [Table of contents](#table-of-contents)
   * [Introduction to Systems](#introduction-to-systems)
     * [What is system?](#what-is-system)
     * [Block Diagram](#block-diagram)
     * [Communication Systems](#communication-systems)
     * [Control Systems](#control-systems)
        * [Open loop](#open-loop)
        * [Closed loop](#closed-loop)
     * [MEMS](#mems)
     * [Remote Sensing](#remote-sensing)
     * [Biomedical Signal Processing](#biomedical-signal-processing)
     * [Auditory Systems](#auditory-systems)  
   * [Properties Of Systems](#properties-of-systems)
      * [Memory](#memory)
      * [Stability](#stability)
      * [Linearity](#linearity)
      * [Causality](#causality)
      * [Invertibility](#invertibility)
      * [Time Invariance](#time-invariance)
   * [LTI Systems](#lti-systems)
      * [Introduction](#introduction)
      * [Impulse response of LTI](#impulse-response-of-lti)
      * [Frequency response of LTI](#frequency-response-of-lti)
      * [Relationship between Frequency and Impulse Response](#relationship-between-frequency-and-impulse-response)
      * [Difference equation Representation of LTI System](#difference-equation-representation-of-lti-system)
   * [Causality](#causality)
      * [Laplace transform causality constraints](#laplace-transform-causality-constraints)
      * [Z transform and causality, stability](#z-transform-and-causality-stability)
   * [Integration of Systems](#integration-of-systems)
      * [Cascading](#cascading)
      * [Parallel](#parallel)
      * [Feedback](#feedback)
<!--te-->

Introduction to Systems
=================

What is system?
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/fxGZ7GRQMsk/0.jpg)](http://www.youtube.com/watch?v=fxGZ7GRQMsk)

Time stamps: <br>
&nbsp;&nbsp; 0:34 - 1:55 Introduction <br>
&nbsp;&nbsp; 1:56 - 4:51 Types of Systems <br>

<b> Description: </b> <br>
<p>
In this Video, he described the system as a source which manipulates the given input signal. With a system we can perform many operations on input signals and get the desired output.
He also mentioned the types 0f systems which are continuous and discrete systems. And then he discusses them.
</p>

Block Diagram
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/X4hPVxZlrPU/1.jpg)](http://www.youtube.com/watch?v=X4hPVxZlrPU)

Time Stamps: <br>
&nbsp;&nbsp; 0:42 - 4:22 Introduction of the Mechanism of Block Diagrams <br>

<b>Description:</b> <br>
<p>
Lecture is about how to represent the signal transformation using a block diagram. He described every block for a particular operation. 

Block diagram consists of : 

Blocks – these represent subsystems – typically modeled by, and labeled with, a transfer function

Signals – inputs and outputs of blocks – signal direction indicated by arrows – could be voltage, velocity, force, etc.

Summing junctions – points were signals are algebraically summed –subtraction indicated by a negative sign near where the signal joins the
summing junction.
For adding signals we use summation junctions and also closed loop systems for performing iterative operations on the input signals. This lecture covers block diagrams used to represent control systems, methods of manipulation of block diagrams (including an Example) as well as covering steady state errors and their determination.
</p>


Communication Systems
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/qhjj6WG7Rgc/2.jpg)](http://www.youtube.com/watch?v=qhjj6WG7Rgc)

Time Stamps: <br>
&nbsp;&nbsp; 1:34 - 8:32 Basic Structure of Block Diagrams <br>

<b>Description:</b> <br>
<p>
In this video, we can understand the basic structure of communication systems with a block diagram.
Below is the block diagram of the communication system.
Communication is the exchange of information between the two or more points.
Electronics point of view, it is the exchange of information using the electronic device or gadget between two or more points which can be far away from each other.
The communication system contains the following basic blocks:

1) The Source
2) Input Transducer
3) Transmitter
4) Channel 
5) Receiver
6) Output Transducer

Source:
The source is the origin from where the message signal is generated.
The message could be voice signal, email, Television Signal, or data.

Input Transducer:
Using the input transducer, the message signal is converted into the electrical signal.

Transmitter:
The transmitter signal modifies the input signal for efficient transmission.
The transmitter may contain several subsystems like modulator, analog to digital converter, encoder, amplifier etc.

Channel:
The channel is the medium over which the transmitted signal is transmitted.
The channel could be physical channel (e.g optical fiber, coaxial cable) or wireless channel (radio link)
The channel partly behaves like a filter and attenuates and distorts the transmitted signal.

The receiver:
For faithful communication, the receiver should be able to recover the message signal from the received (distorted and attenuated) signal.
The receiver also contains several subsystems like, demodulator, decoder, digital to analog converter, amplifier.

Output Transducer:
The output of the receiver is given to the output transducer. Speaker, monitor screen are examples of the output transducer.


</p>

Control Systems
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/O-OqgFE9SD4/3.jpg)](http://www.youtube.com/watch?v=O-OqgFE9SD4)

Time Stamps: <br>
&nbsp;&nbsp; 0:00 - 1:14 Open Loop <br>
&nbsp;&nbsp; 3:38 - 4:10 Closed Loop <br>

<b>Description:</b> <br>
<p>
This video is about the control systems and their types, A control system is a mechanical state that alters the future state of a system. 
Control system is of two types:
Open loop 
Closed loop

Open loop: 
In this system, input signal is not controlled by any feedback from output or conditions. The system is automatic. It continues to alter the input until the given time. Example: Dishwasher which  keeps on cleaning the dishes until the timer stops, it doesn't check whether the dish is clean or not. Once the timer stops it discontinues the process.

Closed loop:
	In this system, it has a regulation for the input before altering in the plant unlike open loop, closed loop system controls the input signal through feedback system.

</p>

MEMS
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/j9y0gfN9WMg/hqdefault.jpg)](http://www.youtube.com/watch?v=j9y0gfN9WMg)

Time Stamps: <br>
&nbsp;&nbsp; 26:24 - 29:32 Characteristics of MEMS

<b>Description:</b> <br>
<p>
Micro Electro-Mechanical Systems are devices built with micro sensors and mechanical parts along signal processing circuits. These devices provide a channel between computing systems and the physical world. Basic I/O ’s are built using MEMS. They provide I/O to information systems like sensing and creating motion, radio waves etc. 
The distinctive features of MEMS :
1. Miniaturization 
2. Multiplicity
3. Microelectronics.

</p>


Remote Sensing
-----------
<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/N49PzLDUIFQ/hqdefault.jpg)](http://www.youtube.com/watch?v=N49PzLDUIFQ)

Time Stamps: <br>
&nbsp;&nbsp; 0:30 - 3:08 Fundamentals of Remote Sensing

<b>Description:</b><br>
<p>
In this video, we learn about the term remote sensing. As it was coined by the US scientist Evelyn L. Pruitt, the term remote sensing means understanding or studying the information of the characteristics of an object or phenomena through a recording device without any physical contact.
</p>

Biomedical Signal Processing
-------------------------------
<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/l9GBf0sTk4s/hqdefault.jpg)](http://www.youtube.com/watch?v=l9GBf0sTk4s)

Time Stamps: <br>
&nbsp;&nbsp; 4:03 - 11:55 Signal Processing(Block Diagram)

<b>Description:</b> <br>
<p>
Biomedical signals are the observations of physical activities of various human body systems. Biomedical signals have two characteristics, they are: number of points used to collect data, type of potential. And also discussed the processing of a biomedical signal.	
</p>

Auditory Systems
-----------
<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/SU_aecxckRg/hqdefault.jpg)](http://www.youtube.com/watch?v=SU_aecxckRg)

Time Stamps: <br>
&nbsp;&nbsp; 0:00 - 2:36 Auditory Systems

<b>Description:</b> <br>
<p>
The human auditory system is composed of three parts. The outer ear , the middle ear and the inner ear. Let's see how it works. 

The sound waves are picked up by the ear pavilion of the outer ear . They are then amplified and transmitted to the middle ear through the external ear canal . This movement of the sound makes this small membrane called the eardrum vibrate.  

These vibrations are transmitted to the ossicles located in the middle ear. The ossicles are the smallest bones in the human body.  They are composed of the malleus, which transmits the vibrations to the incus then to the stapes which acts as a piston that compresses the fluid of the inner ear . 

The cochlea is the main organ of auditory perception.  It contains between 15 to 20 thousand hair cells that detect vibrations of the liquid and generate nerve impulses that are sent to the brain via the auditory nerve.

But this system is fragile and can suffer failures, we call this hearing loss two of which are conduction hearing loss and sensorineural hearing loss. 

Conduction hearing loss can be caused by an obstruction in the ear canal , such as ear wax, a perforated eardrum , a malfunction of the ossicles , otitis or fluid in the middle ear. This type of loss can often be resolved by medical intervention and represents only 10 % of cases of hearing loss.

The second type of loss, sensorineural hearing loss represents 90 % of cases. It results from the destruction of hair cells in the cochlea. It is often due to aging, can be genetic or the consequence of repeated exposure to very loud sound. This type of loss is irreversible, yes, it's a shame, but can often be compensated by hearing aids.
</p>

Properties Of Systems
=================

Memory
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/4PUcOf0koxw/hqdefault.jpg)](http://www.youtube.com/watch?v=4PUcOf0koxw)

Time Stamps: <br>
&emsp;&nbsp; 7:21 - 10:58 &emsp; Memory of System and Memoryless System <br>
&emsp;&nbsp; 1:05 - 15:50 &emsp; Memory System <br>

<b>Description: </b> <br>

<b>Memoryless system:</b> <p>The system is said to be memoryless (in both continuous-time and discrete-time) if its output signal only depends on the present value of the input signal.
The input from the past and future has no influence on the output of the system.

Ex: A resistor is memoryless, since the current i(t) flowing through it in response to the applied voltage v(t) is defined by <br />
&emsp; &emsp;![pic1](https://user-images.githubusercontent.com/54907384/124416411-9030e380-dd74-11eb-8aed-cb313be15533.png) where R is resistance of the resistor.</p>

<b>Memory System:</b> <p>
In contrast, the system is said to possess memory if its output signal depends on past or future values of input signal.
These systems are opposite of memory systems.

Ex: An inductor has memory, since the current i(t) flowing through it is related to the applied voltage v(t) by <br />
&emsp;&emsp; ![pic2](https://user-images.githubusercontent.com/54907384/124416946-bb680280-dd75-11eb-8ff9-a1062a25bb4a.png) where L is inductance of th inductor.</p>

Stability
-----------

<b>Video: </b> <br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/a3b_2VVmkPA/hqdefault.jpg)](http://www.youtube.com/watch?v=a3b_2VVmkPA)

Time Stamps: <br>
&emsp;&nbsp; 0:43 - 8:55 &emsp; Stability stable & Unstable system <br>
&emsp;&nbsp; 11:46 - 20:33 &emsp; BIBO Stable <br>

<b>Description: </b> <br>

<b>Stable System:</b> <p>A system is said to be bounded-input, bounded-output (BIBO) stable (in both continuous-time and discrete-time) if and only if every bounded input results in a bounded output.

i.e., if the output of the system satisfies the condition 
 ![pic3](https://user-images.githubusercontent.com/54907384/124418668-9ffef680-dd79-11eb-9153-df230707c25b.png) <br />
whenever the input of the system satisfies the condition 
![pic4](https://user-images.githubusercontent.com/54907384/124418710-bb6a0180-dd79-11eb-88ee-6c59c99be411.png) <br />
Both Mx and My represent some finite positive numbers.</p>

<b>Unstable system:</b> <p>A system is said to be unstable if it is not a stable system. <br />
Ex: &emsp; &emsp; ![pic5](https://user-images.githubusercontent.com/54907384/124418772-da689380-dd79-11eb-9fbf-7035ad0d3e57.png)

Lets assume the input is bounded and satisfies the condition. &emsp;
![pic6](https://user-images.githubusercontent.com/54907384/124418880-0c79f580-dd7a-11eb-9236-2d9232dd810e.png) <br />
Then we can find that &emsp;
![pic7](https://user-images.githubusercontent.com/54907384/124418897-16035d80-dd7a-11eb-92f8-2e25cc41a655.png) <br />

** When <b>r ≥ 1</b>, r^n increases as n increases and the magnitude of y[n] increases, thus violates the bibo stable condition. So, the system is  unstable.

** When <b>r < 1</b>, r^n decreases as n increases and the magnitude of y[n] reaches zero, thus satisfiying the bibo stable condition. So, the system is  stable.</p>

Linearity
-----------

<b>Video: </b> <br> 
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/wOQDGvCLOs8/hqdefault.jpg)](http://www.youtube.com/watch?v=wOQDGvCLOs8)

Time Stamps: <br>
&emsp;&nbsp; 0:51 - 9:10 &emsp; Linearity superposition <br>
<b>Description: </b> <br>

 <b>Linear system:</b> <p>A system is said to be linear (in both continuous-time and discrete-time) if it satisfies the two properties of superposition and homogeneity.</p>

<b>Superposition:</b> <p>Consider a system that is initially at rest. Let the system be subjected to the input x(t) = 	x1(t), producing an output y(t) = y1(t). Next the same system is subjected to the different input x(t) = x2(t), producing an output y(t) = y2(t). Then for the system to follow superposition property, the corresponding input x(t) = x1(t) + x2(t) should produce corresponding output y(t) = y1(t) + y2(t).</p>

<b>Homogeneity:</b> <p>Consider a system that is initially at rest, and an input x(t) results in output y(t). Then for the system to exhibit the homogeneity property, whenever the system x(t) is scaled by a constant a. The ouput y(t) should also be scaled by the exact constant a (i.e., if input is a.x(t), then output must be a.y(t) ).</p>

Ex: &emsp; y[n] = n.x[n] is a linear system, because it satisfies both  superposition principle and homogeneity property.

If input x[n] is expressed as weighted sum <br />
&emsp; &emsp; &emsp; ![pic8](https://user-images.githubusercontent.com/54907384/124420704-95def700-dd7d-11eb-81a3-8313e6bc3f7f.png) <br />
then the resulting output will be <br />
&emsp; &emsp; &emsp; ![pic9](https://user-images.githubusercontent.com/54907384/124420750-a4c5a980-dd7d-11eb-9dd8-6e2accc59f8a.png) <br />
&emsp; &emsp; &emsp; ![pic10](https://user-images.githubusercontent.com/54907384/124420785-b60eb600-dd7d-11eb-8606-8feadc43ec50.png)

<b>Non-linear System:</b> <p>If the system violates either of the superposition principle or homogeneity property, then it is said to be a Non-linear system.

Ex:
      &emsp;&emsp;y(t) = x(t) + 2t <br />
     &emsp;&emsp; First we will check superposition theorem <br />
      &emsp;&emsp;&emsp;    y1(t) = x1(t) + 2t <br />
      &emsp;&emsp;&emsp;    y2(t) = x2(t) + 2t <br />
     &emsp;&emsp;&emsp;     y1(t) + y2(t) = x1(t) + x2(t) + 4t <br />

&emsp;&emsp;When input x(t) = x1(t) + x2(t), <br />
&emsp;&emsp;&emsp;y(t) = x1(t) + x2(t) + 2t <br />
&emsp;&emsp;Since, both are not equal, the system is Non-linear.</p>
	
Causality
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/mqwUtn5cip8/hqdefault.jpg)](http://www.youtube.com/watch?v=mqwUtn5cip8)

Time Stamps: <br>
&emsp;&nbsp; 00:58 - 07:00 &emsp; Causal System <br>
&emsp;&nbsp; 07:01 - 08:30 &emsp; Non-causal System <br>

<b>Description: </b> <br>

<b>Causal System:</b> <p>A system is said to be causal (in both continuous-time and discrete-time) if the present value of the output signal depends only on the present or past values of the input signal.</p>

Ex: &emsp; &emsp; ![pic11](https://user-images.githubusercontent.com/54907384/124421206-8f9d4a80-dd7e-11eb-974b-8ccf2831968c.png)

<b>Non-causal System:</b> <p>A system is said to be non-causal if it is not a causal system.</p>

Ex: &emsp; &emsp; ![pic12](https://user-images.githubusercontent.com/54907384/124421229-9e83fd00-dd7e-11eb-8172-d2c8f7574ecb.png)

Invertibility
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/06-xo-xAELs/hqdefault.jpg)](http://www.youtube.com/watch?v=06-xo-xAELs)

Time Stamps: <br>
&emsp;&nbsp; 00:51 - 08:24 &emsp; Inverse of a system <br>
&emsp;&nbsp; 08:26 - 10:11 &emsp; Non-Inverse of system <br>

<b>Description: </b> <br>

<b>Invertibile System:</b> <p>A system is said to be Invertible (in both continuous-time and discrete-time) if the input of the system can be recovered from the output. <br />
If H is impulse response of a system, then there should exist another system with impulse response Hinv such that <br />
   &emsp; &emsp; &emsp; ![Screenshot from 2021-07-05 10-50-59](https://user-images.githubusercontent.com/54907384/124421372-f6226880-dd7e-11eb-9483-3f8444f7c725.png)
Where I is a identity operator. <br />

&emsp; &emsp; &emsp; ![aaaaa](https://user-images.githubusercontent.com/54907384/124421423-105c4680-dd7f-11eb-9ffe-9cd774f096e3.png) <br />
Ex: &emsp;
        y(t) = 2x(t)

<b>Non-invertibile System:</b> A system is said to be Non-invertible if the input of system is not recoverable. i.e., there doesn’t exist a system with impulse response Hinv. 

Ex: &emsp; ![Screenshot from 2021-07-05 10-52-58](https://user-images.githubusercontent.com/54907384/124421494-308c0580-dd7f-11eb-9bc7-f31b99268fa4.png) </p>

Time Invariance
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/LezLNMznZm4/hqdefault.jpg)](http://www.youtube.com/watch?v=LezLNMznZm4)

Time Stamps: <br>
&emsp;&nbsp; 00:13 - 04:19 &emsp; Time-Invariance <br>

<b>Description: </b> <br>

<b>Time invariant system:</b> <p>A System is said to be time invariant if a time delay or time advance of the input signal leads to an identical time shift in the output signal. i.e., the time invariant system responds identically no matter when the signal is applied.
If H is impulse response of the system, and St0 represents a time shift of t0 seconds. Then, time invariant system satisfies &emsp;
![Screenshot from 2021-07-05 10-54-51](https://user-images.githubusercontent.com/54907384/124421610-734ddd80-dd7f-11eb-8bb7-057f73533e27.png)

Ex: &emsp; y(t) = t.x(t)

<b>Time variant system:</b> A System is said to time variant if it is not a  time invariant system. i.e., the time delay or time advance of the input may not be identical to the time shift of the output. For the time variant system &emsp;
![Screenshot from 2021-07-05 10-56-11](https://user-images.githubusercontent.com/54907384/124421725-b14b0180-dd7f-11eb-805a-7778f2c6a81a.png)

Ex:&emsp; &emsp; ![Screenshot from 2021-07-05 10-56-17](https://user-images.githubusercontent.com/54907384/124421705-a6906c80-dd7f-11eb-950f-34da4430611c.png)

LTI Systems
=================

Introduction
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/Y8iFJVmSQIk/hqdefault.jpg)](http://www.youtube.com/watch?v=Y8iFJVmSQIk)
	
Time Stamps: <br>
&emsp;&nbsp; 00:35 - 02:20 &emsp; Introduction <br>

<b>Description: </b> <br>
	
<p>&emsp;LTI system is composed of 2 types of systems, <b>linear system</b> and <b>time-invariant system</b>, and possess the properties of both systems.<br />
&emsp;&emsp;&emsp;&emsp;&emsp; [aaaaab](https://user-images.githubusercontent.com/54907384/124428118-e5c3bb00-dd89-11eb-82e2-fd1c1870c0a3.png) </p>
	
Impulse response of LTI
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/CmSlO-wG1V0/hqdefault.jpg)](http://www.youtube.com/watch?v=CmSlO-wG1V0)

Time Stamps: <br>
&emsp;&nbsp; 02:31 - 18:02 &emsp; Impulse Response <br>

<b>Description: </b> <br>
	
<p><b>&emsp;&emsp;Impulse response</b> of a system is its output when presented with a brief input signal, called an impulse. More generally, an impulse response is the reaction of a system in response to some external change. <br />
  
  &emsp;A <b>linear time-invariant (LTI)</b> system can be represented by its <b>impulse response</b> 
&emsp;If X(t) is the input signal to the system, the output, Y(t), can be written as <br />
&emsp;&emsp;&emsp; ![Screenshot from 2021-07-05 11-37-14](https://user-images.githubusercontent.com/54907384/124424948-7c41ad80-dd85-11eb-8a04-bf3cac57358d.png) <br />
&emsp;The above integral is called the convolution of h and X, and we write <br />
&emsp;&emsp;&emsp;&emsp;![Screenshot from 2021-07-05 11-37-27](https://user-images.githubusercontent.com/54907384/124425071-a6936b00-dd85-11eb-8a50-d641e96b4fca.png) <br />
  
  &emsp; For <b>discrete-time systems</b>, the output can be written as <br />
  &emsp;&emsp;&emsp;&emsp;![Screenshot from 2021-07-05 11-40-36](https://user-images.githubusercontent.com/54907384/124425213-e22e3500-dd85-11eb-93ca-06a88ba58e90.png) </p>


Frequency response of LTI
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/E3QfYXscsCc/hqdefault.jpg)](http://www.youtube.com/watch?v=E3QfYXscsCc)

Time Stamps: <br>
&emsp;&nbsp; 00:00 - 02:56 &emsp; Frequency Response <br>

<b>Description: </b> <br>

As per video, <b>Frequency response</b> tells how the system responds to <b>sinusoids of different frequencies</b>. <br>
&emsp;&emsp;&emsp;&emsp; ![Screenshot from 2021-07-05 12-00-44](https://user-images.githubusercontent.com/54907384/124427250-c11b1380-dd88-11eb-9710-0b3e4707897d.png)



Relationship between Frequency and Impulse Response
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/E3QfYXscsCc/hqdefault.jpg)](http://www.youtube.com/watch?v=E3QfYXscsCc)

Time Stamps: <br>
&emsp;&nbsp; 02:57 - 09:32 &emsp; Relationship of Frequency
and Impulse Response <br>

<b>Description: </b> <br>

Relationship between Frequency response and impulse response of the system will be <b>determined by Fourier series and Fourier Transforms</b>.

Difference equation Representation of LTI System
-----------

[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/mRfFUUwfcG0/hqdefault.jpg)](http://www.youtube.com/watch?v=mRfFUUwfcG0)

Time Stamps: <br>
&emsp;&nbsp; 00:00 - 19:11 &emsp; Difference equation representation <br>

<b>Description: </b> <br>

<p>Mainly, we will see <b>linear constant-coefficient difference / differential equations.</b><br />
  
 &emsp; <b>Linear constant-coefficient differential equation: </b> <br />
 &emsp; &emsp;&emsp;&emsp;&emsp; ![Screenshot from 2021-07-05 11-46-53](https://user-images.githubusercontent.com/54907384/124425842-c4ad9b00-dd86-11eb-9a9d-9b9f607c8ac7.png) <br />
  
  &emsp; <b>Linear constant-coefficient difference equation:</b> <br />
&emsp; &emsp;&emsp;&emsp;&emsp;
![Screenshot from 2021-07-05 11-48-48](https://user-images.githubusercontent.com/54907384/124426008-03dbec00-dd87-11eb-8a80-896636809fd6.png) <br />
&emsp;  The order of the differential or difference equation is (N,M), (Often, N >= M)

Causality
=================

Laplace transform causality constraints
-----------

<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/5PbNR3TdFWU/hqdefault.jpg)](https://www.youtube.com/watch?v=5PbNR3TdFWU)

Time Stamps: <br>
&nbsp;&nbsp; 1:20 - 5:00 Introduction to Stable and Causal Laplace Transform <br>
&nbsp;&nbsp; 5:00 - 11:50 Causality Condition in DETAIL


<b>Description:</b> <br>
<p>

In this video, we learn about laplace transform conditions for a system to be causal. 
For a system h(t) to be causal h(t) = 0, t < 0
For a system h(t) to be stable it needs to satisfy BIBO condition,

<img src="https://render.githubusercontent.com/render/math?math=\int_{-\infty }^{\infty }|h(t)|\, dt<\infty">

Causal systems are regions of convergence in s domain that are right sided including infinity conditions.
I.e, laplace transform X(s) =  <img src="https://render.githubusercontent.com/render/math?math=\int_{0}^{\infty }h(t)e^{-st}\, dt">

	
</p>

Z transform and causality, stability
-----------

<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/WoPB-s6V8X0/hqdefault.jpg)](https://www.youtube.com/watch?v=WoPB-s6V8X0)

Time Stamps: <br>
&nbsp;&nbsp; 0:00 - 2:50 Introduction to Causality <br>
&nbsp;&nbsp; 8:15 - 11:28 Causality Condition in Z-Transforms in DETAIL <br>


<b>Description:</b> <br>
<p>

In this video, we learn that a discrete time LTI system with function H(z) is causal if and only if the ROC is the exterior of a circle outside the outermost pole. 

A causal LTI system with function H(z) is stable if and only if 
all the poles of H(z) lie inside the unit circle, i.e, they all must have magnitude smaller than 1. 
An LTI system is stable if and only if the ROC of its system function H(z) includes the unit circle |z| = 1.

</p>

Integration of Systems
=================

Cascading
-----------

<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/5-LWNQkIzS8/hqdefault.jpg)](http://www.youtube.com/watch?v=5-LWNQkIzS8)

Time Stamps: <br>
&nbsp;&nbsp; (0:00-19.10)After this point, Total Voltage Gain starts. If you feel like that has any sort of relevance with the block diagram earlier, you can watch it.

<b>Description:</b> <br>
<p>
A cascaded system is a series or sequential arrangement of objects. In the video, measuring the resultant response of the system in a general cascaded system. 
H(z) = H1(z) x H2(z) x ….. x Hn(z).
</p>

Parallel
-----------

<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/5-LWNQkIzS8/hqdefault.jpg)](http://www.youtube.com/watch?v=5-LWNQkIzS8)

Time Stamps: <br>
&nbsp;&nbsp; (0:00-19.10)After this point, Total Voltage Gain starts. If you feel like that has any sort of relevance with the block diagram earlier, you can watch it.

<b>Description:</b> <br>
<p>
A Parallel system is a parallel arrangement of objects. In the video, measuring the resultant response of the system in a general cascaded system.
H(z) = H1(z) + H2(z) + H3(z) +...... + Hn(z).
</p>

Feedback
-----------

<b>Video: </b><br>
[![IMAGE ALT TEXT HERE](https://i1.ytimg.com/vi/ua4eMZTxpQ0/hqdefault.jpg)](http://www.youtube.com/watch?v=ua4eMZTxpQ0)

Time Stamps: <br>
 (You can start from 0:30, Khan Academy Mechanism only by the way. This video describes working in an efficient way.)

<b>Description:</b> <br>
<p>
Back in 1920, Bell Labs proposed the theory of feedback where the output is given as a limiter or remainder for the flow of input so that we can control the input and system. 
Feedback is the design technique where a portion of the amplifier output "feeds back" to the input of the amplifier. The overall effect creates a very stable gain factor determined by resistor ratios.
</p>	
