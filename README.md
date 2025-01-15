Prescription Recommendation and Mortality Prediction using GPT-3.5

🌟 Overview

This project leverages GPT-3.5, accessed via the OpenAI API, for medical tasks such as prescription recommendation and mortality prediction. By combining the power of PyHealth for medical data processing with GPT-3.5’s natural language understanding, the project demonstrates a novel approach to assist healthcare professionals in clinical decision-making using the MIMIC-III dataset.

🧠 Project Goals
	1.	Prescription Recommendation: Generate tailored prescription suggestions based on patient medical records.
	2.	Mortality Prediction: Evaluate mortality risks using clinical notes and structured patient data.

🛠️ Technologies and Tools
	•	OpenAI API: Accessed GPT-3.5 for natural language processing tasks.
	•	PyHealth: Streamlined handling of MIMIC-III data for preprocessing and feature extraction.
	•	MIMIC-III Dataset: A publicly available, de-identified clinical dataset for critical care research.
	•	Python: Utilized for data manipulation, integration, and API communication.
	•	Prompt Engineering: Designed prompts to optimize GPT-3.5 outputs for medical tasks.

⚙️ Implementation

1. Data Processing with PyHealth
	•	Extracted and preprocessed structured patient records, including clinical notes, lab values, and demographic information, using PyHealth.
	•	Mapped patient data into formats suitable for GPT-3.5 querying.

2. Prompt Engineering
	•	Designed task-specific prompts:
	•	Prescription Recommendation: Input patient medical summaries to retrieve medication suggestions.
	•	Mortality Prediction: Provide structured patient data and clinical notes to assess mortality risks.

3. Model Integration
	•	Combined PyHealth’s preprocessing pipeline with OpenAI’s GPT-3.5 to deliver predictions:
	•	Batch processing for multiple patient records.
	•	Controlled response generation with structured prompts.

🧪 Results
	•	For both the tasks, the model does not seem to exceed or perform really well. This project was a scratch on the surface and more time needs to be put into exploring the usage of LLMs in the field of healthcare.

🚀 Future Directions
	•	Fine-Tuning: Explore integrating domain-specific fine-tuning of GPT-3.5 for better performance on clinical tasks.
	•	Scalability: Expand the use of PyHealth to include larger datasets for broader validation.
	•	Ethical Considerations: Ensure outputs meet ethical standards in medical AI applications, including fairness and bias mitigation.

📚 References
	•	[MIMIC-III Dataset](https://physionet.org/content/mimiciii/1.4/)
	•	[OpenAI API Documentation](https://platform.openai.com/docs/overview)
	•	[PyHealth Documentation](https://pyhealth.readthedocs.io/en/latest/)

Special thanks to [Professor Zijun Yao](https://sites.google.com/view/zijunyao/) to put me into exploration of this research topic of using LLMs for prompting on healthcare dataset.