---
layout: about
title: about
permalink: /
subtitle: >
  PhD Student, <a href="https://www.ece.ucr.edu/">ECE</a> · <a href="https://www.ucr.edu/">UC Riverside</a> ·
  Advised by <a href="https://profiles.ucr.edu/app/home/profile/yhua">Prof. Yingbo Hua</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Bourns College of Engineering</p>
    <p>University of California, Riverside</p>
    <p>mrafi013@ucr.edu</p>

news: true
selected_papers: true
social: true
---

I am a third-year PhD student in Electrical and Computer Engineering at UC Riverside,
working in [Hua's Lab](https://www.ece.ucr.edu/) under the supervision of
[Professor Yingbo Hua](https://profiles.ucr.edu/app/home/profile/yhua).
My research is funded by the U.S. Department of Defense (AFRL/ARL).

My research spans **physical-layer security**, **deep generative models for wireless systems**,
**reconfigurable intelligent surfaces (RIS)**, and **LEO satellite channel modeling and anomaly detection**.
I develop theory, algorithms, and GPU-accelerated simulations at the intersection of
information-theoretic security and modern machine learning.

**Current research threads include:**

- **STEEP protocol** — a novel physical-layer security protocol designed and developed in our lab,
  providing information-theoretic security guarantees that hold even against quantum-capable eavesdroppers.
  My work extends STEEP to finite constellations (PSK, APSK, QAM, PCS-QAM), deriving secret-key capacity
  and secrecy rate, validating gains at the coded level via 5G NR LDPC simulation, and analyzing
  stochastic eavesdropper threats using Poisson Point Process geometry.

- **Deep generative models for wireless anomaly detection** — developed conditional VAE (cVAE) and
  conditional Normalizing Flow (cFlow) models for unsupervised anomaly detection on real Starlink
  LEO satellite drive-test telemetry (22,958 samples), achieving AUROC 0.916 and strong detection
  across scheduling failures, beam obstruction, and complete link failures.

- **Physics-based LEO satellite channel simulation** — built a high-fidelity simulator modeling
  a two-shell LEO constellation using Keplerian + J2 propagation, Saastamoinen tropospheric refraction,
  and a 3GPP TR 38.821 Ka-band link budget, generating per-timestep handover telemetry including
  SINR, Doppler shift, and handover latency for ML benchmarking.

- **Domain-adaptive RIS beam selection via DANN** — developed a domain-adversarial neural network
  framework for reconfigurable intelligent surface beam selection under LOS-to-NLOS propagation shifts,
  using MLP and CNN backbones trained on 3GPP geometry-based stochastic channel datasets.

I received my M.S. in ECE from UC Riverside (GPA 3.90/4.00) and my undergraduate degree from
Islamic University of Technology (IUT), Bangladesh, where I received the Best Paper Award at EECSI 2021.
I am an IEEE Student Member and a recipient of the UC Riverside Dean's Distinguished Fellowship (2023).
