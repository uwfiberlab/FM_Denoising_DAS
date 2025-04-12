
# FM_Denoising_DAS

This repository contains code for an ML denoiser that is one of the tasks of an overall foundation model.

## Project Overview

The goal of this project is to develop and evaluate methods for denoising DAS signals to improve downstream processing. The approach leverages time-frequency transformations and deep learning to enhance signal quality.

## Getting Started

Follow the steps below to set up the project locally.

---

## Prerequisites

- Python 3.8 or later  
- Git  
- [conda](https://docs.conda.io/en/latest/miniconda.html) or [virtualenv](https://virtualenv.pypa.io/en/latest/)

---

## Clone the Repository

```bash
git clone https://github.com/uwfiberlab/FM_Denoising_DAS.git
cd FM_Denoising_DAS
```

---


Create a new conda environment using the provided `env.yml`:

```bash
conda env create -f env.yml
conda activate fm_denoising_das
```

## Project Structure

```
FM_Denoising_DAS/
├── data/               # Contains raw or preprocessed DAS data (not included)
├── models/             # Saved model checkpoints and architectures
├── env.yml             # Conda environment definition
├── main.py             # Main entry point
└── README.md           # Project documentation
```

---

## Contact

For questions or collaboration inquiries, please reach out to the [UW Fiber Lab](https://uwfiberlab.github.io/) or open an issue in this repo.
