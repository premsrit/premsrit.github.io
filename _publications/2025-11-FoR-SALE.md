---
title: "FoR-SALE: Frame of Reference-guided Spatial Adjustment in LLM-based Diffusion Editing"
collection: publications
category: preprints
permalink: /publication/2025-11-FoR-SALE
excerpt: 'We introduce FoR-SALE, a diffusion editing framework that incorporates spatial Frame of Reference reasoning to improve text-to-image generation. By detecting and correcting FoR misalignment between language and vision, FoR-SALE enhances spatial accuracy and improves state-of-the-art model performance by up to 5.3\%.
'
date: 2025-09-27
venue: 'Preprint, Arxiv'
paperurl: 'https://aclanthology.org/2025.emnlp-main.1772.pdf'
citation: 'T. Premsri, P. Kordjamshidi. &quot;FoR-SALE: Frame of Reference-guided Spatial Adjustment in LLM-based Diffusion Editing&quot; <i>Preprint</i>. 2025.'
---


# Abstract

Frame of Reference (FoR) is a fundamental concept in spatial reasoning that humans utilize to comprehend and describe space. With the rapid progress in Multimodal Language models, the moment has come to integrate this long-overlooked dimension into these models. In particular, in text-to-image (T2I) generation, even state-of-the-art models exhibit a significant performance gap when spatial descriptions are provided from perspectives other than the camera. To address this limitation, we propose Frame of Reference-guided Spatial Adjustment in LLM-based Diffusion Editing (FoR-SALE), an extension of the Self-correcting LLM-controlled Diffusion (SLD) framework for T2I. For-Sale evaluates the alignment between a given text and an initially generated image, and refines the image based on the Frame of Reference specified in the spatial expressions. It employs vision modules to extract the spatial configuration of the image, while simultaneously mapping the spatial expression to a corresponding camera perspective. This unified perspective enables direct evaluation of alignment between language and vision. When misalignment is detected, the required editing operations are generated and applied. FoR-SALE applies novel latent-space operations to adjust the facing direction and depth of the generated images. We evaluate FoR-SALE on two benchmarks specifically designed to assess spatial understanding with FoR. Our framework improves the performance of state-of-the-art T2I models by up to 5.3% using only a single round of correction.

---

<div align="center">
  <img src="/images/Figures_FoRSLD_pipeline0.png" alt="Pipeline for FoR-SALE" width="100%">
  <br>
  <em>Pipeline of FoR-SALE framework.</em>
</div>


---