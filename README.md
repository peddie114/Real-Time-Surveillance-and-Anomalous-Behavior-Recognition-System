1.1 Motivation & Expectations
Motivation:
I am passionate about the application of artificial intelligence in surveillance systems. I aim to build a system that can detect potentially dangerous behaviors in real time by combining deep learning models at different levels, thereby improving monitoring efficiency and public safety.
Expectations:
I expect to learn and apply cutting-edge techniques such as object detection, action recognition, and sequential modeling. I also look forward to gaining hands-on experience in data fusion and system integration. Ultimately, I plan to develop a prototype system with real-world application value.
1.2 Learning Outcomes and Experience Sharing
Learned how to leverage cloud platforms (Google Colab) for deep learning model training and inference.
Gained in-depth knowledge of the UCF-Crime and AVA datasets, understanding their characteristics and differences, as well as mastering data preprocessing, feature engineering, and model tuning.
Experienced the challenges and rewards of integrating multiple modules, learning to coordinate video-level anomaly detection with person-level action recognition for real-time surveillance.
Acquired valuable feedback through performance evaluation and real-case testing, which further enhanced our ability to fine-tune the models.

                                                                              Introduction


1.1 Background
Current surveillance systems often rely on traditional image processing techniques or rule-based methods, which tend to suffer from delayed responses and high rates of false alarms or missed detections when identifying anomalous behaviors (such as fighting, theft, or violent incidents). With the rapid development of deep learning and big data analytics, approaches using convolutional neural networks (CNN), 3D CNNs, LSTM, etc., have emerged as popular research directions for detecting anomalous behaviors. Moreover, with the rise of smart cities and the Internet of Things (IoT), it has become increasingly critical to quickly and accurately identify potential dangerous behaviors from surveillance footage and promptly issue alerts.
1.2 Motivation
Technical Motivation:
To explore the application of artificial intelligence in detecting anomalous behaviors—specifically by integrating video-level anomaly detection with person-level action recognition—to improve the system’s overall accuracy and real-time performance.
Practical Motivation:
In the field of surveillance, promptly detecting and marking suspicious behaviors can significantly enhance emergency response and reduce potential risks. By leveraging the complementary features of the UCF-Crime and AVA datasets, our approach offers clear advantages in terms of multi-scale information fusion.
1.3 Objectives
Input:
Continuous frames captured from surveillance cameras or offline videos (extracted PNG images and video clips).
Model Functionality:
Video-Level Anomaly Detection Model: Generates an anomaly score for each video clip to determine whether suspicious or extreme behavior exists.
Person Detection and Action Recognition Model: Uses YOLOv8 and the AVA model to locate persons in the suspicious clip and classify their actions, ultimately overlaying bounding boxes and labels on the frames.
Output:
Statistical anomaly scores and detailed results from person detection and action recognition, visually presented on the real-time monitoring interface along with charts (e.g., histograms) showing the distribution of anomaly scores.
Expected Benefits:
To create a system capable of automatically detecting and marking suspicious behaviors in surveillance footage, thereby reducing false alarms and improving response times. This system can serve as a technical reference for future smart surveillance applications.




