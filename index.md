---
layout: home
title: Home
---

<div class="home-grid">

<div class="sidebar">

<!-- PLACEHOLDER: Replace images/headshot.jpg with your photo -->
<img class="headshot" src="{{ '/images/headshot.jpg' | relative_url }}" alt="{{ site.title }}">

<div class="icon-row">
  <a href="{{ site.scholar_url }}" title="Google Scholar"><i class="ai ai-google-scholar ai-lg"></i></a>
  <a href="{{ site.orcid_url }}" title="ORCID"><i class="ai ai-orcid ai-lg"></i></a>
  <a href="{{ site.cv_path | relative_url }}" title="CV"><i class="ai ai-cv ai-lg"></i></a>
  <a href="{{ site.twitter_url }}" title="X"><i class="fab fa-x-twitter"></i></a>
  <a href="https://github.com/{{ site.github_username }}" title="GitHub"><i class="fab fa-github"></i></a>
  <a href="https://www.linkedin.com/in/sandeep-kambhampati-4b7726162/" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
  <a href="mailto:{{ site.email }}" title="Email"><i class="fas fa-envelope"></i></a>
</div>

</div>

<div class="content" markdown="1">

## About

<!-- PLACEHOLDER: Write your bio here. 2-3 paragraphs about your research interests, current position, and background. -->

I am a 5th year PhD candidate in the [Bioinformatics and Integrative Genomics (BIG)](https://dbmi.hms.harvard.edu/education/phd-program/big-phd-track) program through the [Department of Biomedical Informatics (DBMI)](https://dbmi.hms.harvard.edu/) at Harvard Medical School. I am fortunate to be advised by [Dr. Fei Chen](https://www.insitubiology.org/), who is a core institute member at the [Broad Institute](https://www.broadinstitute.org/).

My research is focused on using machine learning to study "spatial biology" i.e. the study of molecules and cells in their native spatial context. I am particularly interested in understanding how cells process information to achieve structured spatial organization and how this organization is disrupted in disease. Compared to other domains such as natural images and language, biological data is expensive to collect and often exhibits low signal-to-noise ratios. My research is therefore driven by a philosophy of building scalable, data-efficient model architectures that reflect biologically meaningful inductive biases.

Previously, I received my B.S. in Biomedical Engineering from Johns Hopkins University in 2021. I am a recipient of the National Science Foundation Graduate Research Fellowship Program (GRFP). During Summer 2025, I was a Research Intern on the BioML team at [Microsoft Research New England](https://www.microsoft.com/en-us/research/lab/microsoft-research-new-england/), where I worked with [Dr. Alex Lu](https://www.alexluresearch.com/). 

## Papers (selected)

<div class="paper-entry">
  <div class="paper-title">
    <a href="https://www.cell.com/cell-systems/abstract/S2405-4712(25)00227-3">TissueMosaic: Self-supervised learning of tissue representations enables differential spatial transcriptomics across samples</a>
  </div>
  <div class="paper-authors">
    <strong>S. Kambhampati</strong>, L. D'Alessio, F. Grab, S. Fleming, S. Liu, R. Raichur, F. Chen#, M. Babadi#
  </div>
  <div class="paper-venue">
    Cell Systems, 2025. Presented at RECOMB 2025, <a href="https://www.youtube.com/watch?v=70cF-_COWx4">2025 EWSC Symposia</a>, and 2024 Keystone Symposia
  </div>
  <div class="paper-links">
    <a href="https://www.cell.com/cell-systems/abstract/S2405-4712(25)00227-3">[Paper]</a>
    <a href="https://github.com/broadinstitute/TissueMosaic">[Code]</a>
  </div>
</div>

<div class="paper-entry">
  <div class="paper-title">
    <a href="https://www.nature.com/articles/s41586-023-06837-4">Slide-tags enables single-nucleus barcoding for multimodal spatial genomics</a>
  </div>
  <div class="paper-authors">
    A.J.C. Russell*, J.A. Weir*, N.M. Nadaf*, M. Shabet, V. Kumar, <strong>S. Kambhampati</strong>, ..., E.Z. Macosko#, F. Chen#
  </div>
  <div class="paper-venue">
    Nature, 2024
  </div>
  <div class="paper-links">
    <a href="https://www.nature.com/articles/s41586-023-06837-4">[Paper]</a>
  </div>
</div>

<div class="paper-entry">
  <div class="paper-title">
    <a href="https://www.liebertpub.com/doi/10.1089/cmb.2021.0349">Cross-Organ Transcriptomic Comparison Reveals Universal Factors During Maturation</a>
  </div>
  <div class="paper-authors">
    <strong>S. Kambhampati*</strong>, S. Murphy*, H. Uosaki, C. Kwon
  </div>
  <div class="paper-venue">
    Journal of Computational Biology, 2022
  </div>
  <div class="paper-links">
    <a href="https://www.liebertpub.com/doi/10.1089/cmb.2021.0349">[Paper]</a>
  </div>
</div>

## Manuscripts in Preparation

<div class="paper-entry">
  <div class="paper-title">
    DALI Learns Rules Generating Spatiotemporal Transcriptomics
  </div>
  <div class="paper-authors">
    S. Bhate*, <strong>S. Kambhampati*</strong>, M. Babadi, F. Chen#, C. Uhler#
  </div>
  <div class="paper-venue">
    Submitted to ICLR GEN2 Workshop, 2026
  </div>
  <div class="paper-links">
    <a href="https://github.com/broadinstitute/latent-dynamical-systems">[Code]</a>
  </div>
</div>

<div class="paper-entry">
  <div class="paper-title">
    Vermeer: Autoregressive Modeling Enables In Silico Generation of Fluorescent Microscopy Data
  </div>
  <div class="paper-authors">
    <strong>S. Kambhampati</strong>, E. Hayir, E. Zimmermann, K. Yang, F. Chen#, A. Lu#
  </div>
</div>


</div>

</div>
