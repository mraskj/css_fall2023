# Computational Methods and Analysis of Political Text, Audio and Images
This repository contains material for gradudate course "Computational Methods and Analysis of Political Text, Audio and Images" taught in the Fall of 2023 at Aarhus University.




<h2 align="left" id="setup">Setup ⚙️</h2>
Tested for Python 3.8.4 (all version of Python 3.x should work...)

### 1. Create Python3.x environment

`python -m venv .venv` (where `.venv` is the name of virtual environment)

Activate environment using the bash shell:

* `.venv\Scripts\activate` (Windows)

*  `source .venv/bin/activate` (Unix or MacOS)


### 2. Install PyTorch2.0, e.g. for Linux and Windows CUDA11.7:

`conda install pytorch==2.0.0 torchvision==0.15.0 torchaudio==2.0.0 pytorch-cuda=11.7 -c pytorch -c nvidia`

See other methods [here.](https://pytorch.org/get-started/previous-versions/#v200)

### 3. Install this repo

`pip install git+https://github.com/m-bain/whisperx.git`

If already installed, update package to most recent commit

`pip install git+https://github.com/m-bain/whisperx.git --upgrade`

If wishing to modify this package, clone and install in editable mode:
```
$ git clone https://github.com/m-bain/whisperX.git
$ cd whisperX
$ pip install -e .
```

You may also need to install ffmpeg, rust etc. Follow openAI instructions here https://github.com/openai/whisper#setup.
