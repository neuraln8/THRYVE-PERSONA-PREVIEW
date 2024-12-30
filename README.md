
# NN8 PERSONA PREVIEW THRYVE 

## Description
This is a simple chatbot application built with Streamlit and Groq Cloud API. The chatbot uses a system prompt for a persona and interacts with users through a user-friendly interface.

## Setup Instructions

### Prerequisites
- Python 3.7+ installed

### Steps to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/chatbot_project.git
   cd chatbot_project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your API keys in the `.env` file:
   ```env
   GROQ_API_URL=https://api.groq.cloud/v1/chat
   GROQ_API_KEY=your_groq_cloud_api_key
   ```

4. Run the chatbot:
   ```bash
   streamlit run app/chatbot.py
   ```

5. Open the URL in your browser (e.g., `http://localhost:8501`) and start chatting.

### Security Note
Make sure to keep the `.env` file secure and add it to `.gitignore` to prevent sensitive information from being exposed.

## Project Structure
```
chatbot_project/
│
├── app/
│   └── chatbot.py          # Main application code
├── .env                    # API keys and sensitive information
├── .gitignore              # Files to ignore in version control
├── requirements.txt        # Python dependencies
└── README.md               # Project instructions
```

## License
This project is licensed under the MIT License.
