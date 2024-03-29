---
layout: page
title: Projects
permalink: /projects/
---


# Natural Language Interfacing w/ Cozmo using GPT-3.5
#####  [![link to repo](/files/source.jpg)](https://github.com/rhopatel/15-494/tree/master/final) Apr 2023 - May 2023
- Built a Python-based system that takes user text input and automatically generates a syntactically-correct Finite State Machine (FSM) file using GPT-3.5, and executes the program on the robot in real-time
- Optimized accuracy and program validity through prompt engineering to base model *gpt-3.5-turbo*
- Found that GPT occasionally showcased its own flair - when prompted to "spin in a circle", it generated the following:

![robot](/files/robot.jpg)

&nbsp;

# Exploring Golf Analytics From Trackman System: Consistency and Clustering Analysis
#####  [![link to repo](/files/source.jpg)](https://github.com/rhopatel/golf-project) Jan 2023 - May 2023

- Assisted the CMU varsity golf team (Div III) as a statistical consultant for a capstone project
- Collaborated in a small team to analyze indoor golf simulator data from the state-of-the-art TrackMan system to provide actionable insights to the golf team coach, for the individual athlete and overall team
- Wrote code in R (using packages such as ggplot2 and the tidyverse suite) to produce high-quality data visualization to complement in-depth statistical modeling & analysis
- Our [poster](https://www.stat.cmu.edu/capstoneresearch/493files/poster1.pdf) won second place at CMU Meeting of the Minds, a showcase competition for undergraduate research

![driver](/files/driver.png) ![spin_loft_club](/files/spin_loft_club.png)

&nbsp;

# NeuroTechX SC Hackathon: EEG-based painting software
#####  [![link to repo](/files/source.jpg)](https://github.com/rhopatel/SSVEP_Painter) Sep 2022 - Dec 2022

- The first project of my club ([Tartan Neurotech](http://www.tartanneurotech.org/)) in the NeuroTechX 2022 Student Clubs Hackathon, an international neurotech competition
- Led student teams to design & implement hands-free painting software, using ML to decode SSVEP brain signals and increase accessibility for motor-impaired users, with the goal of integrating eye-tracking control with neural signals for a seamless experience
- Built a basic software in Python to test SSVEP signals with rotating icons, recorded signals with OpenBCI Ganglion hardware (below):

![plot_from_flashing_15hz](/files/plot_from_flashing_15hz.png)


&nbsp;

# Attention-Based Speech Recognition
##### [![link to repo](/files/source.jpg)](https://github.com/rhopatel/IDL-hw4) Nov 2022 - Dec 2022 

- Built an end-to-end speech recognition system using attention mechanisms (from the [Listen, Attend and Spell paper](https://arxiv.org/pdf/1508.01211v2.pdf)), implementing a transformer architecture using NumPy and PyTorch to enable high-accuracy speech transcription on the LibriSpeech dataset

- Acheived a final (private score) Levenshtein distance of 12.23 on Kaggle, after training for 30 epochs and employing techniques such as label smoothing, frequency masking, locked dropout, and weight decay

- Part of the final assignment for Introduction to Deep Learning (11-485) @ CMU

![LAS_1](/files/LAS_1.png) ![LAS_2](/files/LAS_2.png) ![LAS_3](/files/LAS_3.png)

&nbsp;
# Beyond DDM: adding learning to drift-diffusion
##### [![link to repo](/files/source.jpg)](https://colab.research.google.com/drive/1D1k-6XTM7OOSJ-ujCeK9YSQA6lc_xuvL?usp=sharing) Nov 2022 - Dec 2022

- Researched and implemented the Drift-Diffusion Model (DDM) of cognitive psychology (a model for decision making in the brain) using the Sequential Probability Ratio Test to compare hypotheses

- Extended the DDM by generalizing the model to remove underlying assumptions (distribution, mean, variance, etc), and applied supervised machine learning using a Support Vector Machine (from scikit-learn) to enable the model to learn from data

![DDM](/files/DDM.png) ![DDM_2](/files/DDM_2.png)

&nbsp;


# Gaussian Mixture Models for Unsupervised Spike Train Sorting
##### [![link to repo](/files/source.jpg)](https://github.com/rhopatel/ps6) Mar 2022 - Apr 2022
- Implemented the Expectation-Maximization algorithm for Gaussian Mixture Models (GMM) in MATLAB to perform neural spike train sorting, as part of an assignment for Neural Signal Processing (42-632) @ CMU 
- Built a unsupervised learning system for neural decoding (classification of spike trains), reached rapid convergence on clusters for real neural data provided by the Shenoy lab

![NSP_1](/files/NSP_1.jpg) ![NSP_2](/files/NSP_2.jpg)


&nbsp;


# Neural Image Reconstruction Using Gabor Filter Regression
##### [![link to repo](/files/source.jpg)](https://github.com/rhopatel/tangImageReconstruction) Jul 2021 - Nov 2021

- Investigated a Gabor-filter linear regression approach towards decoding images from highly sparse 2-photon calcium imaging data from the primate V1 cortex. Final results were mixed with a correlation coefficient of 0.43 between original and reconstruction, but worked well for simple patterns such as a leopard's fur (see below)

- Trained model on an existing dataset gathered in 2018 by Dr. Shiming Tang et. al. ([Large-scale two-photon imaging revealed super-sparse population codes in the V1 superficial layer of awake monkeys](https://elifesciences.org/articles/33370)), includes gigabytes of neural responses to natural & artificial visual stimuli

- Conducted research as part of a summer role in the Lee Lab for Biological & Machine Intelligence

![gabor_wavelet](/files/gabor_wavelet.png) ![tuningCurves10](/files/tuningCurves10.png)


![original](/files/original.png) ![reconstruction](/files/reconstruction.png) ![gaborReconstruction](/files/gaborReconstruction.png)



&nbsp;

# ChemCollective Virtual Laboratory
##### [![link to repo](/files/source.jpg)](https://github.com/rhopatel/vlab2) Jul 2020 - Dec 2020

- Developed software for an NSF-sponsored virtual chemistry simulator (ChemCollective) which allows students and educators to design and perform their own lab experiments. Part of a collaborative project between 15+ universities, and free to use for teachers around the world

- Leveraged skills in JavaScript and graphic design to expand the inventory of digital chemistry equipment, adding both form and function


![vlab_3_50](/files/vlab_3_50.png)


&nbsp;

# ProteinEDU
##### [![link to repo](/files/source.jpg)](https://github.com/rhopatel/ProteinEDU) Oct 2019 - Dec 2019

- Developed an educational interactive protein-folding game using Python to teach the users about the interactions between amino
acids in the primary structure of proteins. The game presents each peptide as a challenge, to fold in accordance with biological properties

- Animated using Tkinter, a Python graphics library. Implemented a basic "autosolver" using backtracking to serve as a reference for students

- Part of the final term project for Fundamentals of Programming (15-112) @ CMU

![maxresdefault_50](/files/maxresdefault_50.png)
