# Galaxy Morphology Analysis with Autoencoder

This project investigates **unsupervised galaxy morphology analysis** using rotation-invariant handcrafted features and autoencoder-based latent space learning, based on galaxy samples from the RC3 catalog and SDSS imaging data.

## 🌌 Research Background
Galaxy morphology provides crucial insights into galaxy formation and evolution. With the rapid growth of large-scale sky surveys, automated and scalable morphology analysis methods have become essential.

This work explores an unsupervised framework that combines physically interpretable features with deep representation learning.

## 📊 Data Sources
- RC3 (Third Reference Catalogue of Bright Galaxies)
- Sloan Digital Sky Survey (SDSS)
- Optical bands: u, g, r, i, z

Only sample images and derived features are included in this repository.

## 🧠 Methodology
The pipeline consists of the following steps:

1. **Galaxy image acquisition**
   - RC3-based target selection
   - Adaptive field-of-view cutouts from SDSS

2. **Rotation-invariant feature construction**
   - Radial brightness distribution
   - Angular Fourier features
   - Frequency-domain radial power spectrum

3. **Multi-band feature fusion**
   - Concatenation and standardization

4. **Autoencoder-based latent space learning**
   - Unsupervised feature compression
   - Reconstruction-based training objective

5. **Latent space clustering**
   - Exploration of intrinsic morphology groupings

## 📈 Results
- Stable low-dimensional latent representations
- Meaningful unsupervised clustering patterns
- Clear qualitative morphological consistency across clusters

## 📁 Repository Structure
# galaxy-morphology-autoencoder
Unsupervised galaxy morphology analysis using rotation-invariant features and autoencoder-based latent space learning on RC3 and SDSS data.
