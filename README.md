
• Health-Symptoms-Checker
AI-powered health symptom checker using LLaMA 3 70B Instruct, deployed on IBM watsonx — provides safe, educational health suggestions based on user-described symptoms.
• 🩺 Agentic AI Health Symptom Checker

This project is a symptom analysis assistant built using **LLaMA 3 70B Instruct** and deployed on **IBM watsonx.ai**. It processes natural language symptom descriptions and provides safe, informative health suggestions without offering any medical diagnosis.

• 🔧 How It Works
- Users describe symptoms in natural language (e.g., "I feel feverish and have chills").
- The input is passed to the LLaMA 3 70B model hosted on IBM watsonx.
- The model returns:
  - Possible health conditions (informational only),
  - Urgency level (low/medium/high),
  - Home remedies and when to consult a doctor.

• 🚀 Model Deployment
- **Model Used**: LLaMA 3 70B Instruct (Watsonx Foundation Model)
- **Platform**: IBM Watsonx.ai
- **Deployment Type**: Text Generation
- **Prompt Type**: Instructional + User Input

• 📁 Project Structure
- `watsonx/` – Deployment configs, sample curl/axios/fetch code.
- `prompts/` – Custom system prompt designed to guide the model.
- `docs/` – Presentation and architecture documentation.

