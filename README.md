# Dielectric-Properties-of-Materials

Dielectric materials are fundamental to modern electronics, powering everything from energy storage capacitors to tunable microwave devices. However, discovering optimal dielectric materials remains a complex task due to the intricate interplay between atomic structure, chemistry, and electronic behavior.

With the power of materials informatics, we can decipher these relationships and accelerate the discovery of efficient dielectric materials tailored to specific applications.

This notebook demonstrates how we can combine data, machine learning, and domain knowledge to accelerate the discovery of novel dielectric materials.

What This Project Uses

Computational Datasets:
Dataset of 1,056 materials with DFT-calculated dielectric properties
(Petousis et al., Sci. Data, 2017)
Includes:

Electronic contribution (e_electronic)

Total dielectric constant (e_total)

Machine Learning:

Unsupervised clustering (k-means)

Feature importance analysis

Domain Knowledge Integration:

Crystal symmetry (space_group)

Bond lengths (avg_bond)

Band gap (band_gap)

Key Questions
How do features (e.g., bond lengths, band gap, space group, volume, structure) correlate with dielectric constants?

Can we identify subgroups (e.g., ferroelectrics) with exceptional properties?

What design rules emerge for high-κ or low-loss materials?

