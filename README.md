# Atlas-py

A boilerplate for jupyter notebooks.

**Note** The default name for the conda env is `atlas`. If you want to change it, you need to change the name in the `environment.yml` file.

## Requirements

- [Anaconda](https://www.anaconda.com/distribution/)
-

## Setup

```bash
conda env create -f environment.yml
```

When exporting dependencies, use the following command:

```bash
conda env export > environment.yml
```

## Usage

Start notebook

```bash
jupyter notebook
```
