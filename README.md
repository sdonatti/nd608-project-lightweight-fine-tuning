# Udacity Generative AI Nanodegree

## Apply Lightweight Fine-Tuning to a Foundation Model

Customize a vision transformer ([ViT](https://arxiv.org/abs/2010.11929)) to solve skin cancer classification using low-rank adaptation ([LoRA](https://arxiv.org/abs/2106.09685)).

![teaser](./images/vit-base-patch16-224-skin_cancer_inferences.png)

### Requirements

Download and install [Anaconda Python](http://www.anaconda.com)

### Set-up

Clone the project repository
```
git clone https://github.com/sdonatti/nd608-project-lightweight-fine-tuning.git
```

Install required Python packages
```
cd nd608-project-lightweight-fine-tuning
conda env create -f environment.yml
```

Launch the project Jupyter Notebook
```
conda activate nd608-generative-ai
jupyter notebook LightweightFineTuning.ipynb
```

### License

This project is licensed under the [MIT License](LICENSE)