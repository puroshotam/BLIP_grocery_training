# BLIP_grocery_training

## Dataset
* Store all images in one folder. And also create ```metadata.csv``` file consisting name of image files and caption corresponding to those image files.
* For example: data/train, data/metadata.csv, where train folder consists all the images.

```dataset = load_dataset("imagefolder", data_dir="data",split="train")```

## Training
* Run ```BLIP_training.py```
