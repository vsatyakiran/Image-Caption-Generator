 # Image Caption Generator using Transfer Learning and Encoder-Decoder Architecture
### DataSet and Code
* Get the dataset and code --> [kaggle](https://www.kaggle.com/code/satyakiranv/imagecap-flicker) 
* Know more about --> [VGG16 Model](https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918)
## Description:
This project leverages transfer learning from the VGG16 model combined with an encoder-decoder architecture to generate captions for images.
Transfer learning enables the model to utilize pre-trained weights from VGG16, which has been trained on a large dataset, allowing it to capture meaningful image features effectively.
The encoder processes the image and extracts relevant features, while the decoder generates captions based on these features. The model's performance is evaluated using BLEU score, with a achieved BLEU score of 0.52 indicating reasonable accuracy in generating captions that align with human references.

## Key Features:
* Transfer learning from VGG16 model for efficient feature extraction.
* Encoder-decoder architecture for generating captions.
* Evaluation using BLEU score for assessing caption quality.
* GitHub repository for code sharing and collaboration.

## Future Improvements:

* Fine-tuning hyperparameters for better performance.
* Experimenting with different pre-trained models for feature extraction.
* Incorporating attention mechanisms to focus on relevant parts of the image.
* Enhancing the dataset for broader coverage of image-caption pairs.


