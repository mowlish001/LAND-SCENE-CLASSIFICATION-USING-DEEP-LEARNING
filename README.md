Land Scene Classification Using Deep Learning

This project focuses on classifying aerial images into ten land scene categories: Bareland, Beach, Bridge, Farmland, Parking, Railway Station, Residential, Stadium, Urban Area, and River. The dataset comprises 3,500+ aerial images, each resized to 224x224 pixels.

Three deep learning models—ResNet-50, MobileNetV3, and EfficientNetB3—were employed for classification. ResNet-50 achieved the highest accuracy, making it the preferred model for predicting land scenes. The system effectively classifies images, aiding in land monitoring, urban planning, and environmental studies.

To enhance visual analysis, the project utilizes HSV color space to detect green areas in classified images, improving the identification of vegetation and farmland regions. Additionally, BLIP (Bootstrapped Language-Image Pretraining) is integrated for text summarization, dynamically generating relevant descriptions for each classified image. This eliminates the need for a predefined dataset and provides meaningful insights into the scene.

The system also includes an image randomization feature, where a randomly selected image is classified and analyzed using the best-performing model. The generated text summary is overlaid onto the aerial image, making the system more interactive and informative.

By combining deep learning with advanced image processing and text generation, this project delivers an efficient and scalable solution for aerial image classification. It has potential applications in environmental monitoring, disaster management, and urban development.
