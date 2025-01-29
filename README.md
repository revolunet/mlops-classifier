# MLOps-classifier

Machine learning text classifier GitOps workflow using sklearn, Github actions and ONNX.

Update your datasets and get models trained, built and converted.

Demo: https://revolunet.github.io/mlops-classifier

## Features

- training runs on GitHub actions
- pull requests get evaluation results
- build `skops` and `onnx` models on merge
- the OONX model can run entirely on the browser

## Instructions

- Organise your files in the `./data` folder
- Create a pull request to train and eval the model
- Merge to produce the model files

## Todo

- gestion des accents !
- PR comments in CI
- publish gh-pages demo
