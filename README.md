PersonaVoice

PersonaVoice is a persona-driven AI text and voice generator that doesn't just respond—it roleplays. Whether it's a sarcastic teenager, a polite professor, or an angry customer, this project generates text in a selected persona **and speaks it aloud** using text-to-speech (TTS).  

🎯 Features

Persona-based response generation (e.g., sarcastic teen, polite professor)
Powered by **OpenAI / LLM APIs** for context-aware generation
Text-to-Speech (TTS) conversion using `gTTS` or `ElevenLabs` for spoken output
Optional voice control per persona
Web UI (Streamlit or Flask) for interactive testing


Tech Stack

| Component           | Technology Used      |
|---------------------|----------------------|
| Text Generation     | OpenAI GPT / Mistral |
| Text-to-Speech      | `gTTS`, `pyttsx3`, or `ElevenLabs` |
| Interface (optional)| Streamlit / Flask    |
| Language            | Python               |

Getting Started

Clone the Repository
```bash
git clone https://github.com/yourusername/PersonaVoice.git
cd PersonaVoice
