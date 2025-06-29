

# Image Caption Generator

This project generates natural language captions for images using deep learning and computer vision.  
It uses the Flickr8k dataset and a pretrained VGG16 model to extract features and generate captions using an LSTM-based decoder.

---

## How to Run

> This project is intended to run on Google Colab using 'kagglehub' to download required datasets.

### Steps:

1. Open the notebook:  
   `Image_Caption_Generator.ipynb`

2. Login to Kaggle** using `kagglehub`:
  
   import kagglehub
   kagglehub.login()


3. Download datasets and images**:
  
4. flickr8k_path = kagglehub.dataset_download('adityajn105/flickr8k')
   


5. Continue running all notebook cells to:

   * Preprocess data
   * Load or train the model
   * Generate captions


##  Datasets Used

* 📁 Flickr8k Dataset

  > Contains 8,000 images with 5 captions each.
  > 🔗 [adityajn105/flickr8k on Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)



##  Project Structure


image-caption-generator/
├── Image_Caption_Generator.ipynb   # Main notebook
├── inputs/                         # Sample test images
│   ├── blank.jpeg
│   ├── blur.jpg
│   ├── blurr.jpg
│   ├── text.png
│   ├── 2759860913_f75b39d783.jpg
│   └── 97577988_65e2eae14a.jpg
├── README.md                       # Project documentation


## Requirements

Install the dependencies using:

```bash
pip install tensorflow numpy pillow matplotlib opencv-python kagglehub
```

Or let Colab auto-install them via the notebook cells.




