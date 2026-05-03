---
page_id: roman_imcom
layout: page
title: Image Combination for Roman Space Telescope
description: 
img: assets/img/roman_imcom.jpg
importance: 2
category: work
related_publications: false
---

One challenge for applying current weak lensing analysis tools to the Nancy Grace Roman Space Telescope is that individual images will be undersampled. Our companion paper presented an initial application of Imcom — an algorithm that builds an optimal mapping from input to output pixels to reconstruct a fully sampled combined image — on the Roman image simulations. In this paper, we measure the output noise power spectra, identify the sources of the major features in the power spectra, and show that simple analytic models that ignore sampling effects underestimate the power spectra of the coadded noise images. We conclude by enumerating the next steps in developing an image coaddition pipeline for Roman.


{% include figure.liquid loading="eager" path="assets/img/roman_imcom_shapecoor.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
Figure: Auto-correlation of observed star ellipticity from various coadded images. This includes Drizzle and Imcom images with simple detector
noise models, and GalSim-drawn injected stars from Imcom images. The ellipticity was measured with adaptive moments. Dark grey shaded region shows the required 𝜉+ signal approximated with the requirements on additive shear errors from SRD. Each panel displays the signals corresponding to each bandpass, and “diamond” marker is the positive signal while “square” is the negative signal but taken absolute value. Bottom: Cross-correlation of the sky coordinates and the observed ellipticity of the same sources.