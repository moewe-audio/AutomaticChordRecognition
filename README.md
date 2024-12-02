# CNN-based major / minor piano chord classification

- tested with python version 3.12
- dependencies listed in `requirements.txt` are required.
- utilized data sets are [Audio Piano Traids Dataset](https://zenodo.org/records/4740877) and [jazznet Dataset](https://zenodo.org/records/7192653)
    - follow the link to insspect their dataset cards

## Instructions
**Running the model**: \
To just run the pre-trained model on a provided example extract it and go to `04-CNN-inference.ipynb`.

**Training the model**: \
To train the model please download the [Audio Piano Traids Dataset](https://zenodo.org/records/4740877) and copy the relevant chord examples into the `chords` folder using the script in `00-sort-augmented-data.ipynb`. This dataset can then be further enriched with selected chord types from the [jazznet Dataset](https://zenodo.org/records/7192653).\
Thereafter, follow the scripts in `01-extract-features.ipynb`, `02-split-data.ipynb` and `03-CNN-model.ipynb` to train the model and generate model statistics.