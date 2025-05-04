🔥 Wildfire Detection using Deep Learning
This project focuses on building an AI model to detect and classify wildfire-related conditions, with a special focus on distinguishing fog and smoke in images — a key challenge in real-time environmental monitoring.

🎯 Project Goal
To develop a deep learning model capable of classifying images as "fire" or "no_fire", and to specifically analyze how well the model can distinguish fog from smoke, which often appear visually similar in natural scenes.

🧠 Techniques Used
Transfer Learning using EfficientNetB0 (pretrained on ImageNet)

Image preprocessing and resizing for consistency

Data augmentation to simulate real-world variations (brightness, rotation, noise)

Categorical classification using softmax activation

Evaluation using training/validation accuracy, loss curves, and image-based testing

Model tuning with callbacks like ModelCheckpoint and ReduceLROnPlateau

📊 Key Insights
Achieved ~95% training accuracy

Validation accuracy ranged from 60–85%, revealing overfitting

The model particularly struggles to distinguish fog from smoke

Future improvements will include regularization, better augmentation, and potentially fine-tuning deeper layers of EfficientNet


