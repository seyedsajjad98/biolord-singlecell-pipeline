# Biolord Single-Cell Pipeline

This repository showcases my contribution to a collaborative paper under Prof. Vincenzo Lagani. The project involves training and testing the Biolord model for analyzing gene perturbation responses using single-cell RNA sequencing (scRNA-seq) data.

Biolord is a deep generative framework designed to disentangle known and unknown biological attributes, enabling predictions for unseen genetic perturbations.

## Features

- **Data Preparation**:
  - Integration of Gene Ontology (GO) features for gene relationship modeling.
  - Mapping perturbation attributes to GO terms for enhanced predictions.
- **Model Training**:
  - Memory-efficient Biolord training setup with categorical and ordered attributes.
- **Prediction and Validation**:
  - HPC-ready prediction pipeline for genetic perturbations with validation metrics.

## Usage

This repository is intended for demonstration purposes and is not functional for training or prediction without HPC resources.

For implementation details:
- See the [notebooks/](notebooks/) folder for the Biolord pipeline.
- Refer to the [docs/Biolord-pipeline-guide.ipynb - Colab.pdf](docs/Biolord-pipeline-guide.ipynb - Colab.pdf) for a step-by-step guide.

Dependencies are listed in [environment/requirements.txt](environment/requirements.txt).
## Contribution

This repository highlights my contribution to training and testing the Biolord model using the NormanWeissman2019 dataset. The work was completed in October 2024 and forms part of a scientific publication comparing Biolord with other models like GEARS.
## Resources

This project uses Biolord, a framework developed by the [Nitzan Lab](https://nitzanlab.github.io/).

- [Biolord GitHub Repository](https://github.com/nitzanlab/biolord)
- [Biolord Documentation and Tutorials](https://biolord.readthedocs.io/en/latest/tutorials/biolord_pipeline.html)
## Historical Context

This repository was created to showcase work completed in October 2024 as part of a collaborative paper. The implementation highlights my specific contribution to the project.
