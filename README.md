# watermarking
This project provides an end-to-end framework for digital image watermarking, encompassing both the embedding and extraction phases, enhanced by the power of deep learning. The system aims to achieve a balance between watermark imperceptibility (maintaining image quality) and robustness against various attacks.

Input & Preprocessing: The system starts with an Input Image that undergoes Image Preprocessing for standardization.
Feature Extraction & Encoding: Features are extracted from both the input image and the watermark using Feature Extraction and then encoded by an Encoder Network.
Watermark Embedding: The encoded features and watermark are combined and embedded into the image using the Watermark Embedding module, enhanced by Deep Learning Enhancements and a Residual Block for Efficient Learning to improve robustness. This generates the Marked Cover Image.
Attack Simulation: To test and improve robustness, Attack Simulation (e.g., JPEG Compression, Scaling) is applied to the marked image.
Watermark Extraction: The system then proceeds to Watermark Extraction, where the watermark is extracted from the (potentially attacked) marked image using the Decoder Network.
Output: The process yields the Outputs Extracted Watermark and the Outputs Final Image.

Python
Deep Learning Frameworks ( TensorFlow, PyTorch - were both tested duirng development phase)
Image Processing Libraries ( OpenCV, PIL )
