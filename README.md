# 🤖 AI-Powered Chatbot

An intelligent chatbot built using Natural Language Processing (NLP) to handle customer queries and FAQs, powered by HuggingFace Transformers and deployed via Flask.

---

## 📌 Features

- 🧠 **Contextual Responses** – Understands and responds using a pre-trained conversational model.
- 💬 **Conversational Memory** – Maintains basic context using `DialoGPT`.
- 🗃️ **Logs Conversations** – Stores user interactions in a SQLite database.
- 🌐 **API Endpoint** – Flask-powered `/chat` endpoint for frontend integration.

---

## 🧰 Tech Stack

| Tool       | Purpose                     |
|------------|-----------------------------|
| 🐍 Python   | Core programming language   |
| 🤗 Transformers | NLP model (DialoGPT)        |
| 🔠 NLTK     | Tokenization support        |
| 🔥 PyTorch  | Backend for Transformers    |
| 🌐 Flask    | API deployment              |
| 🗄️ SQLite   | Interaction logging         |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ai-chatbot.git
   cd ai-chatbot
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app

bash
Copy
Edit
python app.py
Test the API Use Postman or cURL:

bash
Copy
Edit
curl -X POST http://127.0.0.1:5000/chat -H "Content-Type: application/json" -d "{\"message\": \"Hello!\"}"
📂 Project Structure
bash
Copy
Edit
├── AI_Powered_Chatbot.ipynb  # Jupyter notebook version
├── app.py                    # Flask app
├── chat_logs.db              # SQLite database
├── README.md                 # Project README
└── requirements.txt          # Python dependencies
✅ Example Output
User: What are your working hours?
Bot: I'm available 24/7 to assist you! 😊

🧠 Model Used
Model: microsoft/DialoGPT-medium
Provider: 🤗 HuggingFace Transformers

📘 To-Do
 Add multi-turn conversation memory

 Integrate with HTML/CSS frontend

 Add voice-to-text support 🎙️

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and share with credits. 🧑‍💻

❤️ Thanks to
HuggingFace

PyTorch

Flask
