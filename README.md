# DEEP-LEARNING-BASED-3D-VISUALIZATION-OF-BLOOD-CELLS-USING-MICROSCOPIC-IMAGING

Welcome to the detailed overview of our project, "Deep Learning-Based 3D Visualization of Blood Cells Using Microscopic Imaging." This initiative is designed to automate the classification of white blood cells (WBCs) while enhancing their interpretation through advanced artificial intelligence and 3D visualization techniques. By integrating a Convolutional Neural Network (CNN) for image classification with interactive 3D models developed using Blender, the system delivers both diagnostic assistance and educational utility. The application accurately identifies four primary WBC types—Lymphocytes, Monocytes, Neutrophils, and Eosinophils—from stained microscopic blood smear images and renders their corresponding 3D structures in real time within a web-based interface. Developed using a Flask backend and powered by Three.js for 3D rendering, the platform bridges the gap between computational analysis and biomedical education, providing an intuitive and accessible tool for clinicians, researchers, and students alike.

## TECHNOLOGY STACK
The project utilizes a robust and modern technology stack to ensure high performance, accuracy, and user interactivity. The backend is developed using Python and Flask, enabling efficient model integration and server-side processing. TensorFlow and Keras are used to build and train the Convolutional Neural Network (CNN) for white blood cell classification. For 3D visualization, Blender is used to model the cells, while Three.js handles the rendering of these models in the web interface. The frontend is built with HTML, CSS, and JavaScript, ensuring a responsive and interactive user experience. This combination of tools supports seamless data flow from image input to real-time classification and visualization.

## METHODOLOGY
The methodology of our project is centered on building a seamless pipeline that combines deep learning for image classification with 3D visualization for enhanced understanding. We began by sourcing high-quality microscopic images of white blood cells (WBCs) from publicly available datasets. These images, representing four major WBC types—Lymphocytes, Monocytes, Neutrophils, and Eosinophils—underwent preprocessing steps such as resizing, noise reduction, contrast enhancement, and normalization. To improve model generalization and address class imbalance, we employed data augmentation techniques like rotation, flipping, and scaling.

For the classification task, we developed a Convolutional Neural Network (CNN) designed to learn and extract intricate morphological features from the blood smear images. The model includes layers such as convolutional layers with ReLU activation, batch normalization for stable training, max pooling for dimensionality reduction, and fully connected layers for classification. The final output layer uses the Softmax function to predict the specific WBC class. The CNN achieved high training and validation accuracy with minimal overfitting, as reflected in our evaluation metrics.

To complement the AI-driven predictions, we created detailed 3D models of each WBC type using Blender, an open-source 3D modeling software. These models provide a dynamic and spatial perspective of the cells, allowing users to interact with and explore their structures in real time. The 3D visualization helps bridge the gap between theoretical knowledge and practical understanding of cellular morphology.

Finally, the entire system was deployed as a user-friendly web application. We used Flask for the backend to handle image uploads, preprocessing, and CNN inference. The frontend was developed with HTML, CSS, JavaScript, and Three.js, which renders the 3D cell models directly in the browser. This integration ensures that users can easily upload an image, receive a prediction, and view the corresponding 3D model—all within a responsive and interactive web environment.

System Architecture

![Proposed Architecture](https://github.com/user-attachments/assets/87f0b716-f488-44a8-a915-7aac0fe52069)

CNN Architecture

![CNN architecture - Advanced](https://github.com/user-attachments/assets/c2eac7bc-2c96-4116-b15d-e8a617244bd7)

## EVALUATION METRICS

Model Accuracy over Epochs

![Model Accuracy](https://github.com/user-attachments/assets/bb75d54b-4fe1-4db9-8323-11eeb339f989)

Model Loss over Epochs

![Model Loss](https://github.com/user-attachments/assets/8d433a0f-3081-46fa-bd93-8d78ef417a5d)

## RESULTS

Initial Interface of Webpage 

![Screenshot 2025-05-25 184808](https://github.com/user-attachments/assets/b71f5167-a4ed-4f60-8337-c981aec09b4c)

Interface of Webpage after Uploading, Predicting and Generating 3D Model of Microscopic Image

![Screenshot 2025-05-25 184735](https://github.com/user-attachments/assets/70d6dd3d-3112-4ac9-8f9c-0d28be4eb2cb)

Maximized View of Generated 3D Structure of Predicted White Blood Cell

![Screenshot 2025-05-25 190349](https://github.com/user-attachments/assets/15749651-9ac5-4e2d-9994-ba208d3d24fc)

## Thank You !!










