---
title: ""
permalink: /research/
toc: false
toc_sticky: false
breadcrumbs: false
---

## Research themes

<div class="card-grid">

<div class="card">
  <div class="card-title"><i class="fas fa-wave-square"></i> Physics-informed ML</div>
  <div class="card-text">Models that respect acquisition physics and remain stable under noise, sparsity, and instrumental effects.</div>
</div>

<div class="card">
  <div class="card-title"><i class="fas fa-layer-group"></i> Multimodal fusion</div>
  <div class="card-text">Joint modeling of images and tabular / photometric features; cross-attention for heterogeneous sensors.</div>
</div>

<div class="card">
  <div class="card-title"><i class="fas fa-shield-alt"></i> Reliability & uncertainty</div>
  <div class="card-text">Uncertainty-aware inference, domain generalization, and calibrated confidence sets for safer deployment.</div>
</div>

</div>

## Selected projects

<div class="project-panel">
  <div class="project-panel__media">
    <a href="https://github.com/srinadh99/COSI-GRBLocalization" target="_blank" rel="noopener">
      <img src="{{ '/assets/images/projects/cosi-grb-localization.png' | relative_url }}" alt="Compton imaging for COSI — project thumbnail">
    </a>
  </div>
  <div class="project-panel__content">
    <h3>ML imaging techniques for Compton cameras (COSI)</h3>

    <div class="project-tags">
      <span class="project-tag">PyTorch</span>
      <span class="project-tag">Compton data space</span>
      <span class="project-tag">Localization</span>
      <span class="project-tag">High-energy astrophysics</span>
    </div>

    <ul>
      <li>Developed a physics-aligned GRB localization pipeline in Compton Data Space (CDS), exploring both unbinned permutation-invariant models and binned 3D CNNs.</li>
      <li>Built a time-resolved COSI light-curve tool used for blind transient searches.</li>
      <li>Contributed to data analysis + scientific software development efforts around the NASA COSI mission.</li>
    </ul>

    <p class="project-links">
      <a class="btn btn--primary btn--small" href="https://github.com/srinadh99/COSI-GRBLocalization" target="_blank" rel="noopener">GitHub: COSI-GRBLocalization</a>
      <a class="btn btn--inverse btn--small" href="https://github.com/srinadh99/Light-Curve-Tool-for-COSI-" target="_blank" rel="noopener">GitHub: Light-Curve-Tool</a>
    </p>
  </div>
</div>

<div class="project-panel">
  <div class="project-panel__media">
    <a href="https://github.com/srinadh99/Astronomical-Source-Classification-using-Machine-Learning" target="_blank" rel="noopener">
      <img src="{{ '/assets/images/projects/margformer.png' | relative_url }}" alt="MargFormer — project thumbnail">
    </a>
  </div>
  <div class="project-panel__content">
    <h3>ML for astronomical source separation (MargFormer)</h3>

    <div class="project-tags">
      <span class="project-tag">Vision Transformer</span>
      <span class="project-tag">Multimodal fusion</span>
      <span class="project-tag">SDSS</span>
      <span class="project-tag">Calibration</span>
    </div>

    <ul>
      <li>Designed a multimodal Vision Transformer that integrates image tiles with photometric (tabular) features for compact-galaxy vs. star/quasar separation.</li>
      <li>Validated on SDSS DR16 and emphasized scaling to next-generation surveys (e.g., Rubin LSST).</li>
      <li>Applied conformal prediction to convert model scores into calibrated confidence sets under domain shift.</li>
    </ul>

    <p class="project-links">
      <a class="btn btn--primary btn--small" href="https://github.com/srinadh99/Astronomical-Source-Classification-using-Machine-Learning" target="_blank" rel="noopener">GitHub: Source-Classification</a>
      <a class="btn btn--inverse btn--small" href="https://github.com/srinadh99/AstroFormer" target="_blank" rel="noopener">GitHub: AstroFormer</a>
    </p>
  </div>
</div>

<div class="project-panel">
  <div class="project-panel__media">
    <a href="https://github.com/srinadh99/VISION-TRANSFORMER-DRIVEN-LIDAR-DATA-FUSION-FOR-ENHANCED-HYPERSPECTRAL-IMAGE-CLASSIFICATION" target="_blank" rel="noopener">
      <img src="{{ '/assets/images/projects/hsi-lidar-fusion.png' | relative_url }}" alt="Hyperspectral + LiDAR fusion — project thumbnail">
    </a>
  </div>
  <div class="project-panel__content">
    <h3>Multimodal data fusion for remote sensing (hyperspectral + LiDAR)</h3>

    <div class="project-tags">
      <span class="project-tag">Remote sensing</span>
      <span class="project-tag">Cross-attention</span>
      <span class="project-tag">Distributed training</span>
      <span class="project-tag">Land-cover</span>
    </div>

    <ul>
      <li>Built ViT-based multimodal fusion frameworks (self-attention and cross-attention) for land-cover classification.</li>
      <li>Evaluated on benchmark datasets (e.g., University of Houston) and implemented scalable training workflows.</li>
      <li>Explored fusion strategies (early / mid / late) to balance shared vs. modality-specific representations.</li>
    </ul>

    <p class="project-links">
      <a class="btn btn--primary btn--small" href="https://github.com/srinadh99/VISION-TRANSFORMER-DRIVEN-LIDAR-DATA-FUSION-FOR-ENHANCED-HYPERSPECTRAL-IMAGE-CLASSIFICATION" target="_blank" rel="noopener">GitHub: ViT LiDAR Fusion</a>
      <a class="btn btn--inverse btn--small" href="https://github.com/srinadh99/Transformer-Models-for-Multimodal-Remote-Sensing-Data" target="_blank" rel="noopener">GitHub: MFT Study</a>
    </p>
  </div>
</div>

<div class="project-panel">
  <div class="project-panel__media">
    <a href="https://github.com/srinadh99/Cosmic-Ray-rejection-with-attention-augmented-deep-learning" target="_blank" rel="noopener">
      <img src="{{ '/assets/images/projects/cosmic-ray-mitigation.png' | relative_url }}" alt="Cosmic-ray mitigation — project thumbnail">
    </a>
  </div>
  <div class="project-panel__content">
    <h3>Detection & masking of transient artifacts in astronomical images</h3>

    <div class="project-tags">
      <span class="project-tag">U-Net</span>
      <span class="project-tag">Artifact detection</span>
      <span class="project-tag">Instrument-agnostic</span>
      <span class="project-tag">Uncertainty</span>
    </div>

    <ul>
      <li>Developed two-stage cosmic-ray hit mitigation: dictionary-learning + patch classification feeding attention-gated U-Nets.</li>
      <li>Targeted generalization across instruments (DECam, LCOGT, HST) with robust masks and improved detection rates.</li>
      <li>Studied Bayesian CNNs to locate regimes where cosmic rays can be confused with astrophysical sources.</li>
    </ul>

    <p class="project-links">
      <a class="btn btn--primary btn--small" href="https://github.com/srinadh99/Cosmic-Ray-rejection-with-attention-augmented-deep-learning" target="_blank" rel="noopener">GitHub: Attention U-Nets</a>
      <a class="btn btn--inverse btn--small" href="https://github.com/srinadh99/Cosmic-Ray-Detection-via-Dictionary-Learning" target="_blank" rel="noopener">GitHub: Dictionary Learning</a>
    </p>
  </div>
</div>


## Selected publications

- **(Journal, 2024)** Enhanced Astronomical Source Classification with Integration of Attention Mechanisms and Vision Transformers. *Astrophysics and Space Science*.
- **(Journal, 2022)** Cosmic Ray rejection with attention augmented deep learning. *Astronomy and Computing*.
- **(Conference, 2024)** Vision Transformer-Driven LiDAR Data Fusion for Enhanced Hyperspectral Image Classification. *IEEE InGARSS*.

<div class="notice--success">
Tip: Click on a project thumbnail to open the corresponding GitHub repository.
</div>
