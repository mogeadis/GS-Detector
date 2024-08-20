# GS-Detector 🎸


## Table of Contents

- [Description](#description)
    - [Project](#project)
    - [Repository](#repository)
    - [Technical Details](#technical-details)
- [Acknowledgements](#acknowledgements)
- [License](#license)


## Description

### Project
**GS-Detector** performs automatic guitar string detection by exploiting the spectral feature of real strings known as *inharmonicity*, for applications such as automatic tablature transcription. The algorithm requires minimal data for adaptation and is designed for use only with monophonic guitar audio recordings, while assuming that the pitch, as well as the onset and offset timestamps of the played notes, are known.

### Repository
The code in this repository is contained in two *Jupyter Notebooks*, namely [`main.ipynb`](main.ipynb) and [`supplement.ipynb`](supplement.ipynb). The former implements and evaluates the proposed guitar string detection algorithm, while the latter demonstrates the process of computing the inharmonicity coefficient. The [*Datasets*](Datasets) utilized for the evaluation of the algorithm are provided in the corresponding directory. Lastly, a relevant unpublished [*paper*](paper.pdf) is also included in the repository for reference. 

### Technical Details
This project was developed exclusively within the computing environment of *Google Colaboratory*, thus the specific version of *Python* used and any package requirements are subject to the up-to-dateness of the service at the time of development. To run the notebooks in your own working environment, please refer to the associated code sections and make any necessary adjustments.

## Acknowledgements

The datasets included in this repository are sourced from the [IDMT-SMT-Guitar](https://www.idmt.fraunhofer.de/en/publications/datasets/guitar.html) dataset by Christian Kehling, Andreas Männchen, and Arndt Eppler. Each dataset directory provided in this repository corresponds to a specific directory within the original dataset as follows:
> Datasets/Bridge Pickup &nbsp;&rarr; IDMT-SMT-GUITAR/dataset1/Ibanez Power Strat Clean Bridge HU\
> Datasets/Middle Pickup &rarr; IDMT-SMT-GUITAR/dataset1/Ibanez Power Strat Clean Bridge+Neck SC\
> Datasets/Neck Pickup &nbsp;&nbsp; &rarr; IDMT-SMT-GUITAR/dataset1/Ibanez Power Strat Clean Neck HU


## License

*GS-Detector* © *2024* by *Alexandros Iliadis* is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

See the [`LICENSE.md`](LICENSE.md) file for more details.