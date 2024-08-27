# SpotBID Set Dataset

This repository contains the SpotBID Set dataset, which was created as part of the research for the paper titled "DocLightDetect: A new algorithm for occlusion classification in identification documents". The dataset is made available for researchers and practitioners interested in studying and improving occlusion classification in identification documents, particularly those caused by the spotlight effect.

# Overview
In the digital era, accurate identification of users through online platforms is crucial, especially for institutions such as banks, insurance companies, and government services. One of the significant challenges in this process is the occurrence of occlusions in images of identification documents, often caused by the spotlight effect when using mobile devices. The SpotBID Set was developed to simulate these scenarios and to provide a robust dataset for testing and improving algorithms like DocLightDetect, which aims to classify such occlusions accurately.

# Dataset Description
The SpotBID Set replicates a mobile video capturing environment, particularly focusing on the spotlight effect. Below is a summary of the dataset creation process:

1. Initial Base Selection: The Smartdoc Dataset was used as the foundation for this dataset. It features documents in a video format, suitable for frame-based analysis.
2. Frame Selection: Images were sampled every 10 frames from the original video to ensure document diversity within the dataset.
3. Document Replacement: The original documents were replaced with Brazilian identification documents such as Open Driver's License, Driver's License Front, Social Security Number Front, and Identity Card Front, sourced from the BID Dataset.
4. Filming Simulation: Documents were integrated into the backgrounds from the Smartdoc Dataset to simulate a realistic filming environment.
5. Spotlight Effect Application: A spotlight effect was applied to the document regions, with light temperatures varying between warm and cool, distributed equally.
6. Occlusion Categorization: The dataset is split into images with and without occlusion.
7. Image Dimensions: Each image has a resolution of 1,920 x 1,080 pixels.
8. Total Images: The dataset contains 22,472 images, evenly split between occlusion and non-occlusion classes.

# Download the Dataset
You can download the SpotBID Set dataset using the following link:

https://drive.google.com/file/d/1U1M6rmO4TXEcErcyYmmFQ8ZOdMjk1hJB/view?usp=sharing
