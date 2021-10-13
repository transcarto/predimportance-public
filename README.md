## Predicting Visual Importance Across Graphic Design Types

Forked for the **TransCarto** thematical school, CNRS, october 2021, to use on special map images.

To execute the iPython Notebook in a Binder Jupyter : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/transcarto/predimportance-public/HEAD)

This repository contains code associated with the project at: http://predimportance.mit.edu/

The model file, in [Keras H5 format](https://www.tensorflow.org/guide/keras/save_and_serialize), can be downloaded [here](http://predimportance.mit.edu/data/xception_cl_fus_aspp_imp1k_10kl-3cc0.1mse-5nss5bc_bs4_ep30_valloss-2.5774_full.h5).

The provided [Jupyter notebook](umsi_simple_inference_from_full_model.ipynb) contains the model specification and shows how to load and run the Keras model on some sample images.

If you use this code, please consider citing:
```
Fosco, C., Casser, V., Kumar Bedi, A., O'Donovan, P., Hertzmann, A., Bylinskii, Z.
Predicting Visual Importance Across Graphic Design Types. In ACM UIST, 2020.
```

Questions? Contact camilolu@mit.edu (or [alternative contacts](http://predimportance.mit.edu/#authors))
