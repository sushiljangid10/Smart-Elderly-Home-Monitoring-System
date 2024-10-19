🏠 Smart Elderly Home Monitoring System
An Integrated Analysis of Gas, Temperature, and Position Sensors for Anomaly Detection & Safety Enhancement
📖 Project Overview
This project focuses on developing and evaluating a Smart Elderly Home Monitoring System 🧓🏡 that integrates gas, temperature, and position sensors to enhance safety by detecting anomalies (e.g., gas leaks, abnormal temperature changes, unusual movement patterns) using advanced machine learning models.

💡 Research Motivation
With the rising elderly population 👵👴 and their preference for aging in place, there’s an urgent need for advanced monitoring solutions that ensure their safety. This project leverages sensor data and machine learning techniques to detect anomalies that may signal potential health or safety risks.

🎯 Research Objectives
Model Evaluation: Assess the performance of various ML models like Autoencoder, Isolation Forest, Local Outliers Factor (LOF), and One-Class SVM in detecting anomalies within smart homes.
Sensor Integration: Explore how integrating gas, temperature, and position sensors impacts accuracy and reliability.
System Implementation: Evaluate the feasibility of deploying the system in real-world scenarios, ensuring scalability and adaptability.
Safety Enhancement: Analyze how timely detection of anomalies can enhance preventive measures and improve overall safety.
🛠️ Methodology
This project follows the CRISP-DM methodology, encompassing:

Data Collection: Gathering sensor data (gas, temperature, position).
Preprocessing: Cleaning and organizing the data.
Model Training & Evaluation: Testing multiple machine learning algorithms to detect anomalies.
Key Tools:

Programming Languages: Python 🐍
Libraries: scikit-learn, TensorFlow
Visualization: Tableau, Matplotlib, Seaborn
📊 Data Visualization & Analysis
Data was visualized using Python libraries and Tableau, providing insightful plots:

Histograms
Line plots
Count plots
Heatmaps
These visualizations reveal relationships between sensor readings and the detected anomalies, helping identify patterns in unusual sensor behavior.

Model	Accuracy
Autoencoder	1.00
Isolation Forest	1.00
LOF	0.90
One-Class SVM	0.03
🏆 Results
Autoencoder and Isolation Forest models achieved perfect accuracy (1.00), proving their effectiveness in identifying subtle anomalies.
The LOF model performed well with an accuracy of 0.90, efficiently identifying local outliers.
One-Class SVM, however, struggled with an accuracy of 0.03, making it less suited for this application.
📈 Conclusion
The study shows great promise for using sensor technologies in enhancing the safety of elderly individuals in smart homes. Particularly, the Autoencoder and Isolation Forest models stand out as reliable for anomaly detection. Future enhancements could focus on integrating more sensors and refining ML models to improve detection accuracy.

🔮 Future Scope
🧩 Expand the sensor network by including additional environmental (e.g., humidity) and physiological (e.g., heart rate) sensors.
⚡ Explore real-time processing techniques to enhance system responsiveness.
🖥️ Develop a user-friendly dashboard for caregivers and family members to remotely monitor the elderly.
