## Fine Tuning Resnet on Caltech 

This notebook shows how to fine-tune a pre-trained ResNet-18 on the Caltech-256 dataset.
It sets up the data loaders, freezes most layers, swaps out the final layer, and trains the model to adapt it to the new dataset.
At the end, it compares predictions from the original pre-trained model and the fine-tuned version to show the improvement.