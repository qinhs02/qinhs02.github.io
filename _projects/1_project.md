---
layout: page
title: Long working distance smartphone microscope
description: Metallic Mesh Defect Detection Based on Low‑Rank Decomposition via Schatten Capped p Norm
img: assets/img/Fig1.png
importance: 1
category: work
related_publications: true
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
Facing the demand of the electromagnetic interference (EMI) shielding applications for metallic mesh detection,
this article introduces a weighted robust principal component analysis (RPCA) method based on the Schatten capped p (SCp) norm, termed SCp-WRPCA, specifically designed for defect identification and measurement. Traditional RPCA techniques often suffer from sub-optimal results and over-shrinkage issues due to conventional nuclear norm minimization. To address these challenges, we integrate the SCp norm with RPCA. This hybrid low-rank model enhances the precision of decomposition by effectively preserving principal singular values and incorporates a noise term to account for various interferences.
SCp-WRPCA stands out for its multidimensional feature fusion for prior extraction, combining an 18-dimensional texture feature map with a neighborhood feature map. To tackle the issue of decomposed sparse results appearing in both positive and negative regions, particularly with multiple defects, we employ hierarchical threshold segmentation, enhancing sparse term utilization. Our proposed optimization problem is solved stably by the alternating direction method of multipliers (ADMM). Through quantitative and qualitative comparisons, SCp-WRPCA demonstrates superiority over existing baselines in our metallic mesh databases and others, including TILDA and HKU fabric databases. This indicates its robust generalization capability in various texton defect detection scenarios.
    ---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Fig1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>


{% endraw %}
