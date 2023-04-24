> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [neuronaldynamics.epfl.ch](https://neuronaldynamics.epfl.ch/online/Ch1.html)

> Freely available online version of the computational neuroscience book "Neuronal Dynamics" written by......

The primary aim of this chapter is to introduce several elementary notions of neuroscience, in particular the concepts of action potentials, postsynaptic potentials, firing thresholds, refractoriness, and adaptation. Based on these notions a preliminary model of neuronal dynamics is built and this simple model (the leaky integrate-and-fire model) will be used as a starting point and reference for the generalized integrate-and-fire models, which are the main topic of the book, to be discussed in Parts [II](https://neuronaldynamics.epfl.ch/online/Pt2.html "Part II Generalized Integrate-and-Fire Neurons ‣ Neuronal Dynamics – From Single Neurons to Networks
and Models of Cognition") and [III](https://neuronaldynamics.epfl.ch/online/Pt3.html "Part III Networks of Neurons and Population Activity ‣ Neuronal Dynamics – From Single Neurons to Networks
and Models of Cognition"). Since the mathematics used for the simple model is essentially that of a one-dimensional linear differential equation, we take this first chapter as an opportunity to introduce some of the mathematical notation that will be used throughout the rest of the book.

Due to the limitations of space we cannot – and do not want to – give a comprehensive introduction into such a complex field as neurobiology. The presentation of the biological background in this chapter is therefore highly selective and focuses on those aspects needed to appreciate the biological background of the theoretical work presented in this book. For an in-depth discussion of neurobiology we refer the reader to the literature mentioned at the end of this chapter.

After the review of neuronal properties in Section [1.1](https://neuronaldynamics.epfl.ch/online/Ch1.S1.html "1.1 Elements of Neuronal Systems ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
and Models of Cognition") and [1.2](https://neuronaldynamics.epfl.ch/online/Ch1.S2.html "1.2 Elements of Neuronal Dynamics ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
and Models of Cognition") we will turn, in Section [1.3](https://neuronaldynamics.epfl.ch/online/Ch1.S3.html "1.3 Integrate-And-Fire Models ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
and Models of Cognition"), to our first mathematical neuron model. The last two sections are devoted to a discussion of the strengths and limitations of simplified models.

*   [1.1 Elements of Neuronal Systems](https://neuronaldynamics.epfl.ch/online/Ch1.S1.html "1.1 Elements of Neuronal Systems ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")

*   [1.2 Elements of Neuronal Dynamics](https://neuronaldynamics.epfl.ch/online/Ch1.S2.html "1.2 Elements of Neuronal Dynamics ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")

*   [1.3 Integrate-And-Fire Models](https://neuronaldynamics.epfl.ch/online/Ch1.S3.html "1.3 Integrate-And-Fire Models ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")

*   [1.4 Limitations of the Leaky Integrate-and-Fire Model](https://neuronaldynamics.epfl.ch/online/Ch1.S4.html "1.4 Limitations of the Leaky Integrate-and-Fire Model ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")

*   [1.5 What Can We Expect from Integrate-And-Fire Models?](https://neuronaldynamics.epfl.ch/online/Ch1.S5.html "1.5 What Can We Expect from Integrate-And-Fire Models? ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")

*   [1.6 Summary](https://neuronaldynamics.epfl.ch/online/Ch1.S6.html "1.6 Summary ‣ Chapter 1 Introduction: Neurons and Mathematics ‣ Part I Foundations of Neuronal Dynamics ‣ Neuronal Dynamics – From Single Neurons to Networks
    and Models of Cognition")