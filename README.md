# UCI Time Series XAI Benchmark
A reference codebase for the UCI Time Series XAI Benchmark. It includes Jupyter notebooks, scripts, and instructions for replicating or extending deep-learning-based time series classification with Anchor, LIME, and SHAP post-hoc explanations.

## Overview

This repository hosts the code and utilities for the UCI Time Series XAI Benchmark, a collection of **multiclass time series** datasets from UCI, each paired with **deep learning models** and **post-hoc explanations** (Anchor, LIME, SHAP). The full dataset (including train/test splits, models, and computed explanations) is available on Zenodo:

**DOI**: [10.5281/zenodo.15173401](https://doi.org/10.5281/zenodo.15173401)

## Contents

1. **Notebooks/**  
   - Jupyter notebooks demonstrating:
     - Model training (deep learning)
     - Computation of Anchor, LIME, and SHAP explanations

2. **Requirements.txt**  
   - Python dependencies for running the notebooks and scripts

3. **LICENSE**  
   - Chosen open-source license for the repository (see below)

4. **README.md**  
   - This file

## How to Use

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YourAccount/uci-time-series-xai-benchmark.git
   cd uci-time-series-xai-benchmark
   ```


2. **Download or link the Zenodo dataset**  
   - Go to [Zenodo link](https://doi.org/10.5281/zenodo.15173401)  
   - Download the `.zip` archives:  
     - `train_test.zip`  
     - `models.zip`  
     - `shap.zip`  
     - `lime.zip`  
     - `anchor.zip`  
   - You may unzip the archives or adapt the notebooks to load directly from zip files.

  3. **Extend or modify**

     You can use this codebase to:
     - Apply the workflow to additional or custom time series datasets.
     - Integrate new explainability methods or variations (e.g., Integrated Gradients, Saliency Maps).
     - Experiment with alternative model architectures or loss functions.
     - Reproduce or extend experiments from the associated publication.

## Contributing

We welcome contributions from the community!

- Open an **Issue** to report bugs, suggest features, or ask questions.
- Submit a **Pull Request** to contribute notebooks, enhancements, documentation improvements, or new explanation methods.

## Citation

If you use this repository or dataset in your research, please cite:

```bash
@misc{uci-time-series-xai-benchmark,
  title        = {UCI Time Series XAI Benchmark},
  author       = {Maciej Mozolewski and Szymon Bobek},
  organization = {Jagiellonian Human-Centered AI Lab, Mark Kac Center for Complex Systems Research, 
                  Institute of Applied Computer Science, Jagiellonian University, Krakow, Poland},
  year         = {2025},
  doi          = {10.5281/zenodo.15173401},
  url          = {https://doi.org/10.5281/zenodo.15173401},
  note         = {Corresponding author: m.mozolewski@doctoral.uj.edu.pl; Contributing author: szymon.bobek@uj.edu.pl}
}

```

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
- **Share** – copy and redistribute the material in any medium or format  
- **Adapt** – remix, transform, and build upon the material for any purpose, even commercially  

Under the following terms:
- **Attribution** – You must give appropriate credit, provide a link to the license, and indicate if changes were made.  
  You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

License text: https://creativecommons.org/licenses/by/4.0/
