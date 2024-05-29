# Incorporating Geometric Contour Variability into a Dosimetric Radiotherapy Quality Assurance System

This repository contains code to generate data for the ISBI 2024 one-page-abstract poster describing the differences between geometric variability and dosimetric effects. This corresponds to the figure on the left in the image below. 

![figure-1 drawio](https://github.com/ubern-mia/geomvar-OAR/assets/6485878/a9f54b3c-c7da-454a-8c0d-fd044c1861ca)

The figure on the right is generated using [ASTRA](https://github.com/amithjkamath/astra), as shown in the corresponding EMBC '23 paper.

TL;DR: measuring the quality of AI-driven automation in the radiotherapy treatment planning process cannot simply be limited to looking at Dice scores for auto-segmentation, or, DVH curves for deep learning dose calculations, but needs to at least be a combination of both. Current literature is awash with new deep learning network architectures promising a test set Dice of 0.9, which is great! However, do the errors that correspond to the remaining volume of 0.1 impact the dose computation adversely? Uncertainties in a preceding step may propagate into complex failure modes into the next: and a holistic quality assurance system must account for these. 

For more, see [LinkedIn post here](https://www.linkedin.com/posts/amithjkamath_after-an-unforgettable-ieee-international-activity-7200872465835720704-6Cli?utm_source=share&utm_medium=member_desktop).

The data needed to reproduce this is unfortunately not in the public domain - please reach out to me if you'd like to learn more. 
