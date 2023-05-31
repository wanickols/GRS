# GRS: Game Recommendation System

## Description

GRS is a project that aims to provide game recommendations based on item-to-item similarity using categorical data. It is built for an AI class using Python notebooks and Anaconda. It uses various libraries and techniques such as pandas, numpy, TRIMAP, WPCA, sklearn, scipy, dateutil, Thread, Queue, Requests, csv, time, collaborative filtering, and neural networks. The project is now on hiatus from me, and won't be recieving regular updates. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

## Installation

To run this project, you need to have Anaconda installed on your system. You can download it from [here](https://www.anaconda.com/products/individual). After installing Anaconda, you need to create a virtual environment and install the required libraries. You can do this by following these steps:

1. Open Anaconda Prompt and navigate to the project folder.
2. Run `conda create -n grs python=3.8` to create a new virtual environment named grs with Python 3.8.
3. Run `conda activate grs` to activate the virtual environment.
4. Run `pip install -r requirements.txt` to install the dependencies from the requirements.txt file.

## Usage

To use this project, you need to have some game data in CSV format. You can use the data provided in the data folder or get more data from online sources such as [Steam](https://store.steampowered.com/). The data should have the following columns: id, name, genre, rating, platforms, tags, release_date.

To run the project, you need to open the notebooks in Jupyter Lab or Jupyter Notebook. You can do this by running `jupyter lab` or `jupyter notebook` in Anaconda Prompt while in the project folder.

The notebooks are organized as follows:

- Data retrieval.ipynb: This notebook contains the code for getting the data from RAWG
- Clean Data.ipynb: This contains the code for cleaning the data into the correct format
- Data Format and Basic Model Training.ipynb:  This notebook contains the code for training the basic model using collaborative filtering and generating a similarity matrix.

To get game recommendations currently, run Data Format and Basic Model Training and change the recommendation variable to a game title. Use WPCA or TRIMAP to reduce dimensionality before getting the metrics. 

## Contribution

This project is mainly developed by me, but I welcome any help or feedback from other developers. If you want to contribute to this project, you can do so by following these steps:

1. Fork this repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them with descriptive messages.
5. Push your changes to your forked repository.
6. Create a pull request from your forked repository to this repository.

Please make sure to follow the code style and conventions of this project and write clear and concise comments.

Please don't edit the data without explaining why!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
