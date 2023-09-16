# Image Captioning


## Introduction
<samp>
Image captioning is a computational task that involves automatically generating descriptive text or captions for images. This technology leverages sophisticated algorithms to analyze the content of an image and produce relevant and coherent textual descriptions. In the modern digital era, image captioning has gained significant importance due to the vast proliferation of images, driven by the widespread use of smartphones and advanced camera equipment. It plays a crucial role in enhancing the accessibility and understanding of visual content, making it a valuable tool for various applications, including content indexing, accessibility features, and assisting individuals in organizing their extensive collections of images.
</samp>

## Features: 
<samp>
- Automated Description: Image captioning automatically creates textual descriptions for images.
<br>
- Visual-Linguistic Fusion: These models understand images and generate human-like captions by combining visual and textual elements.
</samp>

## Future Prospects:
<samp>
- Security/Threat Classification: Combining the output of Image Captioning and applying NLP to classify image based on the caption on whether it's threat or not is one possible prospect in other words video/image security classification is one of the future prospect I could think of using Image Classification.
<br>
</samp>

## Work Flow:
<samp>
- Data Preparation: Collect paired image and text data, preprocess images, and tokenize captions.
<br>
- Feature Extraction: Use ResNet-50 to extract image features.
<br>
- Sequence Model: Employ an LSTM-based decoder for caption generation.
<br>
- Training: Train the model with image-caption pairs using a loss function.
<br>
- Inference: During inference, initialize the decoder with image features and use a greedy algorithm to generate captions one word at a time.
<br>
- Caption Generation: Predict the most likely word at each step based on the current state and previously generated words.
<br>
- Completion: Continue generating words until an end token or a preset maximum length is reached, producing the final image caption.
</samp>

## Tools Used:
<samp>
- Dev Cloud
  <br>
- Intel Extension for Tensorflow
 <br>
- OpenVino
<br>
- Tensor Flow
</samp>

## Integration of OneAPI-tools:
<samp>
DevCloud Utilization: DevCloud provided valuable computational resources for training and inference. It enabled efficient scaling and resource allocation for model training, ensuring timely completion of training tasks.
<br>
Intel Extension for TensorFlow: The project made use of the Intel Extension for TensorFlow to optimize TensorFlow-based operations for better performance on Intel hardware. This extension ensured that the model ran efficiently during both training and inference stages, leveraging the hardware acceleration features.
<br>
OpenVINO Integration: OpenVINO was instrumental in further optimizing the model for efficient inferencing. By converting the model to OpenVINO's format and leveraging its hardware-specific optimizations, the project achieved faster and more efficient image caption generation on Intel hardware, making the system suitable for real-time applications and deployment on a variety of Intel-powered platforms.
</samp>

## Final Output:
![1st Prediction](https://github.com/sanj33krsna/1API-Image_Captioning/blob/main/demo/1.png)
<br>
![2nd Prediction](https://github.com/sanj33krsna/1API-Image_Captioning/blob/main/demo/2.png)

## Future Additions:
[] Addition of an web app using gradio, flask or hugging face space.
