# **Offensive Language Identification in Social Media**
The project presents a method of identification and categorization of offensive language used on social media platforms.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

Nowadays, abusive content spreading in social media poses a serious problem. The offensive language is pervasive and due to the users' anonymity on the Internet, people feel unreachable when it comes to the punishment. As a result, many people may suffer from being insulted. Multiple social media platforms and companies noticed the emerging problem and have already investigated possible solutions. Undoubtedly, one of them is to use computational methods to detect hate speech in various types of utterances posted on the web. Nevertheless, the ability of identifying offense automatically is the first step we would like to undertake. 

The problem is to detect and assign offensive language occurrences to various pre-defined categories using Natural Language Processing methods. A dedicated dataset was created specifically for this task.

## Technologies
* Python 3
* Tensorflow 2.0
* spaCy 2.2

## Setup
Clone the repository and perform one of the following actions:
* Open the jupyter notebook locally, by executing `jupyter notebook Solution.ipynb`
* Open the notebook file in one of the cloud notebooks (e.g. Google Colab).

## Features
* Extensive preprocessing
* Prepared several comparative baselines
* Implemented a whole pipeline for BERT model

To-do list:
* Implement cost-sensitive methods that deal with dataset imbalance
* Fine-tune and test ERNIE model
* Fine-tune and test ALBERT
* Combine the best models in an ensemble

## Status
Project is still in progress.

## Inspiration
Project is based on [OffensEval 2020 Task](https://sites.google.com/site/offensevalsharedtask/). This is the 12th task of one of [SemEval-2020](http://alt.qcri.org/semeval2020/) competition.

## Authors
Created by students from Poznań University of Technology:
* [Piotr Janiszewski](mailto:1piotr.janiszewski@gmail.com)
* Urszula Walińska
* Mateusz Skiba

Feel free to contact us!
