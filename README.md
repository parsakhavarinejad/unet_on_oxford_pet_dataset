
# U-Net on Oxford Pets III Dataset

This project implements U-Net, a convolutional neural network architecture, on the Oxford Pets III dataset. U-Net is particularly effective for image segmentation tasks, which makes it suitable for tasks like pet object detection, instance segmentation, and more.

## Dataset

The Oxford Pets III dataset contains a large collection of images of various pet breeds with corresponding pixel-wise masks for object segmentation. It serves as a benchmark for various computer vision tasks.

The dataset is downloaded from tensorflow datasets API inside the notebook and its size is approximately 770 mg.

## Notebook

To view and interact with the notebook containing the U-Net implementation and experimentations, please open the following file:

[Notebook File](unet-for-oxford-pet-dataset.ipynb)

## Usage

1. Clone the repository:

```bash
git clone https://github.com/parsakhavarinejad/unet_on_oxford_pet_dataset
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook file in Jupyter Notebook or Jupyter Lab.

4. Follow the step-by-step instructions and code cells in the notebook to explore the U-Net implementation, train the model, evaluate results, and visualize predictions.

## Results

The model's accuracy is 81% in just 15 epochs. it can be improved significantly with a better GPU and memory in more epochs.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a GitHub issue or submit a pull request.


