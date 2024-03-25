# The Multi-modality Cell Segmentation Challenge: Towards Universal Solutions

![logo](logo.png) % this is the logo

[Competition](https://neurips22-cellseg.grand-challenge.org/)

[paper](https://www.nature.com/articles/s41592-024-02233-6)

[Data](https://neurips22-cellseg.grand-challenge.org/dataset/)

% this is the main figure behind the above icons. 

![task](task-intro.gif)

## A large and diverse microscopy image dataset

- 50+ different biological experiments
- Four different microscopes
- 900,000+ annotated cells
- Different cell origins, staining methods, morphologies, …


![data](data.png)

![participants](participants.png)

> The geographical distribution of data sources and challenge participants. The red, green, purple, and blue address icons denote the countries or regions where the brightfield, fluorescent, phase-contrast, and differential interference contrast image datasets are from, respectively. The size of the pink circle in each country is proportional
to the number of participants from the corresponding country. 


## The top algorithms set new state of the arts

- The winning team, boasting a Transformer-based architecture, has proven to be a remarkable achievement in cell segmentation.
- Top algorithms demonstrated exceptional accuracy and efficiency, surpassing existing state-of-the-art cell segmentation methods such as Cellpose and Omnipose as well as the top algorithm in the CTC challenge.
- All top algorithms have made the code and models publicly available. 


| Top Teams   | Method | Implementation | Tutorial | Interface | Container |
|-------------|-----------|----------|-----------|------------|------------|
| T1-osilab   | [paper](https://proceedings.mlr.press/v212/lee23a.html) | [Code](https://github.com/Lee-Gihun/MEDIAR) | [Colab](https://colab.research.google.com/drive/1iFnGu6A_p-5s_eATjNtfjb9-MR5L3pLB?usp=sharing) | [Napari](https://github.com/joonkeekim/mediar-napari) | [Docker](https://hub.docker.com/repository/docker/joonkeekim/mediar/general) |
| T2-sribdmed | [paper](https://proceedings.mlr.press/v212/lou23a.html) | [Code](https://github.com/lhaof/CellSeg) | [Colab](https://colab.research.google.com/drive/1Dk6V6vm0IqaIevjAyjUTuR1nZfT6EvCh?usp=sharing) | [Napari](https://github.com/Lewislou/cellseg_sribd_napari ) | [Docker](https://hub.docker.com/repository/docker/lewislou/sribd-cellseg) |
| T3-cells    | [paper](https://proceedings.mlr.press/v212/upschulte23a.html) | [Code](https://github.com/FZJ-INM1-BDA/neurips22-cell-seg) | [Colab](https://colab.research.google.com/drive/1Ycc2X131lmlU50Ds8iz8o0KSgLWDjO9H) | [Napari](https://github.com/FZJ-INM1-BDA/celldetection-napari ) | [Docker](https://hub.docker.com/repository/docker/ericup/neurips22-cell-seg/tags?page=1&ordering=last_updated) |

![result](results.png)

**From SOTA algorithms to biological practice**: The top three best-performing algorithms have been integrated into an open-source and user-friendly [napari](https://github.com/joonkeekim/mediar-napari) interface. Biological researchers can now conveniently apply these advanced segmentation techniques to their own images without necessitating additional coding. 





## bibtex

```
@article{NeurIPS-CellSeg,
title = {The Multi-modality Cell Segmentation Challenge: Towards Universal Solutions},
author = {Jun Ma and Ronald Xie and Shamini Ayyadhury and Cheng Ge and Anubha Gupta and Ritu Gupta and Song Gu and Yao Zhang and Gihun Lee and Joonkee Kim and Wei Lou and Haofeng Li and Eric Upschulte and Timo Dickscheid and José Guilherme de Almeida and Yixin Wang and Lin Han and Xin Yang and Marco Labagnara and Vojislav Gligorovski and Maxime Scheder and Sahand Jamal Rahi and Carly Kempster and Alice Pollitt and Leon Espinosa and Tâm Mignot and Jan Moritz Middeke and Jan-Niklas Eckardt and Wangkai Li and Zhaoyang Li and Xiaochen Cai and Bizhe Bai and Noah F. Greenwald and David Van Valen and Erin Weisbart and Beth A. Cimini and Trevor Cheung and Oscar Brück and Gary D. Bader and Bo Wang},
journal = {Nature Methods},
year = {2024},
doi = {https://doi.org/10.1038/s41592-024-02233-6}
}
```
