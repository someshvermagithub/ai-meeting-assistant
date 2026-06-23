<div align="center">

# 🎬 AI Meeting Assistant

AI-powered Meeting Assistant that transcribes audio/video, translates multilingual content, generates summaries, and enables conversational Q&A using RAG and LLMs.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6E57E0?style=for-the-badge)
![Whisper](https://img.shields.io/badge/OpenAI_Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FF7000?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Under_Development-yellow?style=for-the-badge)

</div>

---

## ✨ Features

* 🎙️ Audio transcription
* 🎥 Video transcription
* 📺 YouTube video processing
* 📝 AI-generated summaries
* ✅ Action item extraction
* 🔑 Key decision extraction
* ❓ Open question detection
* 💬 Chat with your meeting using RAG
* 🌐 Multilingual support
* 📄 PDF and text export

---

## 🚀 Upcoming Features

* 🔥 OpenAI Whisper integration
* 🇮🇳 Sarvam AI Hindi transcription
* 👥 Speaker diarization
* ⚡ Real-time transcription
* 📱 Mobile-friendly interface
* ☁️ Cloud deployment
* 🔊 Multi-language support

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Speech-to-Text

* OpenAI Whisper (Upcoming)
* Sarvam AI (Upcoming)

### LLM & RAG

* LangChain
* Mistral AI
* ChromaDB
* Sentence Transformers

### Audio Processing

* FFmpeg
* Pydub
* yt-dlp

### Utilities

* Python
* NumPy
* Requests
* TQDM

---

## 📂 Project Structure

```text
ai-meeting-assistant/
│
├── core/
│   ├── extractor.py
│   ├── rag_engine.py
│   ├── summarizer.py
│   ├── transcriber.py
│   └── vector_store.py
│
├── utils/
│   └── audio_processor.py
│
├── .env
├── app.py
├── main.py
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-meeting-assistant.git

cd ai-meeting-assistant
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

Windows:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🏗️ Workflow

1. Upload audio/video or provide a YouTube URL.
2. Extract audio.
3. Generate transcript.
4. Create summary.
5. Extract action items.
6. Build vector embeddings.
7. Chat with your meeting.

---

## 🚧 Current Status

| Feature                | Status |
| ---------------------- | ------ |
| Audio Processing       | ✅      |
| Summarization          | ✅      |
| Action Items           | ✅      |
| RAG Chat               | ✅      |
| Streamlit UI           | ✅      |
| Whisper Integration    | 🚧     |
| Sarvam AI Integration  | 🚧     |
| Speaker Identification | 🚧     |

---

## 🐛 Known Issues

* Large videos require high memory.
* Long transcripts may increase response time.
* CPU transcription can be slow.
* GPU optimization is in progress.

---

## 📋 Roadmap

* [ ] Add Whisper transcription
* [ ] Add Sarvam AI Hindi transcription
* [ ] Add speaker diarization
* [ ] Add real-time transcription
* [ ] Add authentication
* [ ] Add cloud deployment
* [ ] Add meeting history
* [ ] Improve PDF exports

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push your changes.
5. Open a Pull Request.

---

## 🏷️ Topics

```
ai
generative-ai
whisper
sarvam-ai
streamlit
langchain
rag
chromadb
speech-to-text
meeting-assistant
python
llm
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Somesh Verma**


Interested in Artificial Intelligence, Generative AI, Data Science, and Machine Learning.

---

⭐ If you find this project useful, consider giving it a star.
