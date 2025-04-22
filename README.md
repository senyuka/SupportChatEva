# Eva – AI Assistant for Customer Support

Eva is a simple conversational assistant for an insurance company. It uses Anthropic's Claude model to simulate helpful, context-aware interactions with users. The app is built with Streamlit and structured for modular development.

## Features

- Streamlit-based web interface
- Claude (Anthropic) integration via API
- Session-aware chat with message history
- Modular code structure

## Project Structure
```
SupportChat/
├── app.py                  # Streamlit app entry point
├── chatbot.py              # Chatbot class using Anthropic
├── config.py               # Constants like TOOLS, IDENTITY, MODEL
├── requirements.txt        # Dependencies
└── .gitignore              # Git ignore settings
```

## Getting Started
1. Clone the repository:

```bash
git clone https://github.com/your-username/SupportChat.git
cd SupportChat
```
2. Install the dependicies
```bash
pip install -r requirements.txt
```

3. Set your Anthropic API key (required to run the assistant):
```bash
export ANTHROPIC_API_KEY=your-api-key
```

4. Run the app:
```bash
streamlit run app.py
```

## Acknowledgements

This project is adapted from examples provided by Anthropic in their [Anthropic Cookbook](https://docs.anthropic.com/en/docs/about-claude/use-case-guides/customer-support-chat).  
All credit for the original architecture and ideas goes to their team.
