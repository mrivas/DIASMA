# Summer class DIASMA: Cellular metabolis estiamtions using transcriptomics


This repository contains a collection of Jupyter notebooks that serve as exercises and tutorials for using  "[computational models of cellular metabolism that are conditioned by transcriptomics](https://www.cell.com/iscience/fulltext/S2589-0042(23)00278-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS258900422300278X%3Fshowall%3Dtrue)". You can download the Jupyter notebooks directly from here (from the folders of this repository).

Contact: Marcelo Rivas Astroza (see our [website](https://www.rivaslab.com))

## Notebooks collected

Notebooks are contained in the subfolders

* `toy-metabolic-networks`<br>
  exercises to build intuition and understanding

* `real-metabolic-networks`<br>
  exercises for real applications in industry and medicine


## User instructions

To get started with Jupyter notebooks, please see the following user instructions.

## Jupyter Notebook - instructions for beginners

This section will guide you through the steps to set up, install dependencies, and use Jupyter Notebook.

### Outline:

1. What is Jupyter Notebook?
2. Prerequisites
3. Installation
4. Getting started

### What is Jupyter Notebook?

Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, plots, and text. Jupyter supports a variety of programming languages, but in this guide, we will primarily focus on Python.

### Prerequisites:

- Python 3.6 or higher -> The main programming language supported in this guide.
- Package Manager -> Either `pip` (the standard package installer for Python) or `conda` (used in Anaconda distributions).
- Web Browser -> Chrome, Firefox, or any other modern browser for running Jupyter Notebook.

**Note** It is recommended to use a Python virtual environment (via `venv` or `conda`) to isolate your project dependencies and avoid potential conflicts with other projects.

### Installation:

#### 1. Installing Jupyter Notebook with `pip`

Run the following command to install Jupyter Notebook using `pip`

```bash
pip install notebook
```

You can verify the installation through

```bash
jupyter --version
```

#### 2. Installing Jupyter Notebook via Anaconda

You need to install Anaconda first from the website: https://www.anaconda.com/products/distribution
You can open Anaconda Navigator and launch Jupyter directly from there, or you can use the command 

```bash
jupyter --version
```

### Getting started:

Once Jupyter is installed, start the Jupyter Notebook server by running the following command

```bash
jupyter notebook
```

This will open a new tab in your default web browser, where you will see the file explorer displaying the contents of your current working directory. From here, you can create a new notebook or open an existing one.

**Note** Jupyter runs locally on http://localhost:8888/ by default. Use this URL to access the interface. You can open an existing Notebook with

```bash
jupyter notebook my_notebook.ipynb
```

### References:

1. [Jupyter Documentation](https://jupyter.org/documentation) - The official documentation for Jupyter.
2. [Project Jupyter GitHub](https://github.com/jupyter) - Source code and contributions to Jupyter.
3. [Anaconda Official Website](https://www.anaconda.com) - Download and learn more about Anaconda.