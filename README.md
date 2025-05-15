# VIP extras

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=binder%2Fwelcome.ipynb)


> additional material for [VIP](https://github.com/vortex-exoplanet/VIP)


## [Tutorials](./tutorials)

Tutorials in form of Jupyter notebooks can be found in the `tutorials/` folder. They can be visualized directly here on GitHub (by just clicking on them), or using the nbviewer service.

### 01. Quick-start Tutorial

#### A. Serial version

> [GitHub](./tutorials/01A_quickstart.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/01A_quickstart.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F01A_quickstart.ipynb)

#### B. Object-oriented version

> [GitHub](./tutorials/01B_quickstart_with_objects.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/01B_quickstart_with_objects.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F01B_quickstart_with_objects.ipynb)

This tutorial covers:

- how to load ADI-ready datacubes; 
- how to use some of the stellar PSF subtraction algorithms implemented in VIP to produce final post-processed images.



### 02. Pre-processing Tutorial

> [GitHub](./tutorials/02_preproc.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/02_preproc.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F02_preproc.ipynb)

This tutorial showcases the pre-processing routines available routines in VIP (i.e. how to prepare a datacube before PSF modeling and subtraction). More specifically, the tutorial shows how to carry out the following tasks:

- recentering of a NACO L' coronagraphic dataset and trimming bad frames out;
- correcting bad pixels and recentering a SPHERE/IFS coronagraphic dataset; 
- performing a "full pre-processing" of a non-coronagraphic SINFONI dataset.


### 03. PSF modeling and subtraction with ADI Tutorial

#### A. Serial version

> [GitHub](./tutorials/03A_psfsub_ADI.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/03A_psfsub_ADI.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F03A_psfsub_ADI.ipynb)

This tutorial covers:

- how to load ADI-ready datacubes; 
- how to use the stellar PSF subtraction algorithms implemented in VIP to produce final post-processed images (more details and higher completeness than the quick-start tutorial).

#### B. Object-oriented version

> [GitHub](./tutorials/03B_psfsub_ADI_as_objects.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/03B_psfsub_ADI.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F03A_psfsub_ADI.ipynb)

This tutorial covers:

- how to load ADI-ready datacubes; 
- how to use the stellar PSF subtraction algorithms implemented in VIP to produce final post-processed images (more details and higher completeness than the quick-start tutorial).


### 04. Metrics Tutorial

> [GitHub](./tutorials/04_metrics.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/04_metrics.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F04_metrics.ipynb)

This tutorial covers:

- how to compute the S/N ratio of a given companion candidate;
- how to calculate the significance of a detection;
- how to compute S/N ratio maps and STIM maps; 
- how to use the automatic point-source detection function;
- how to compute throughput and contrast curves.


### 05A. Forward modeling of point sources Tutorial

> [GitHub](./tutorials/05A_fm_planets.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/05A_fm_planets.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F05A_fm_planets.ipynb)

This tutorial covers:

- how to generate and inject fake companions in a cube;
- how to estimate the astrometry and photometry of a directly imaged companion, and associated uncertainties.


### 05B. Forward modeling of disk Tutorial

> [GitHub](./tutorials/05B_fm_disks.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/05B_fm_disks.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F05B_fm_disks.ipynb)

This tutorial covers:

- how to generate different models of synthetic (debris) disks;
- how to inject model disks in ADI cubes, for forward modeling.


### 06. RDI PSF subtraction and forward modeling

> [GitHub](./tutorials/06_psfsub_fm_RDI.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/06_psfsub_fm_RDI.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F06_psfsub_fm_RDI.ipynb)

This tutorial covers:

- how to load ADI and reference datacubes; 
- how to use the stellar PSF subtraction algorithms implemented in VIP to produce final post-processed images of disks or leveraging the RDI strategy.

### 07. IFS+ADI PSF subtraction and forward modeling Tutorial

> [GitHub](./tutorials/07_psfsub_fm_IFS-ASDI_planets.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/07_psfsub_fm_IFS-ASDIplanets.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F07_ifs_psfsub_fm_planets.ipynb)

This tutorial covers:

- how to inject a planet spectrum in a 4D (IFS+ADI) datacube;
- how to post-process 4D (IFS+ADI) datacubes; 
- how to retrieve the parameters of a planet present in a 4D (IFS+ADI) datacube (astro- and spectrometry).


### 08. FFT-based vs. interpolation-based image operations Tutorial

> [GitHub](./tutorials/08_imlib_and_interpolation.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/08_imlib_and_interpolation.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F08_imlib_and_interpolation.ipynb)

This tutorial shows a quantitative comparison between FFT-based and interpolation-based methods for:

- image rotations;
- image scaling;
- sub-px shifts.


### 09. Dataset Objects Tutorial

> [GitHub](./tutorials/09_datasets_as_objects.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/09_datasets_as_objects.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F09_datasets_as_objects.ipynb)

This tutorial gives an overview of the new *object oriented* way of using VIP.


## [Datasets](./datasets)

The datasets in the `datasets/` folder are available in FITS format, with the fully pre-processed (ADI-ready) datasets also available in VIP's own Dataset format (as `.npz`).

### NACO betapic

Small ADI cube with 39 frames. `naco_betapic.npz` contains just the "raw" data (`cube`, `psf`, `angles`, `px_scale`), while `naco_betapic_preproc.npz` is slightly preprocessed (cropped, psf normalized).

### SPHERE v471tau

ADI+IFS (4D) cube, ideal to test both ADI and SDI functionalities. The cube, psf images, derotation angles and wavelength vector are provided.

### SPHERE PDS 70

ADI+IFS (4D) center cube, ideal to test recentering of SPHERE/IFS data. The center cube, psf images, and wavelength vector are provided.

### SINFONI HD 179218

IFS (3D) cube, ideal to test preprocessing and SDI functionalities. The cube and wavelength vector are provided.

### SPHERE SAO 206462

An IFS (3D) cube taken in star-hopping mode, ideal for testing preprocessing and RDI functionalities. A cube of references is provided.