Groq Chat Assistant
Groq Chat Assistant is an interactive chatbot application built with Streamlit that lets users engage with an AI model in a conversational way. It provides a customizable and dynamic chat experience, tailored to meet various user needs, from simple information gathering to expert advice and creative brainstorming.

Features
AI Model and Persona Selection
Choose between different AI models for optimal performance based on user preferences.
Select conversation styles (personas) like:
Default: Friendly and helpful AI assistant.
Expert: In-depth, technical, and detailed responses.
Creative: Imaginative responses with analogies and creative language.
Contextual Memory
The chatbot remembers recent messages, providing context-aware responses.
Users can set how many previous messages the chatbot remembers for personalized and coherent conversations.
Clear Chat Interface
Displays chat history with easy-to-read formatting for user messages and AI responses.
Includes options to clear chat history and start new conversations.
Real-Time Statistics
Tracks and displays useful chat stats like total message count and chat duration.
Error Handling and Security
Handles any errors gracefully, providing clear feedback to the user.
Keeps sensitive data secure by loading API keys from environment variables.
Project Setup
1. Clone the Repository
git clone <repository-url>
cd <project-folder>
2. Create a Virtual Environment
conda create -p env python=3.10 -y
3. Activate the Virtual Environment
conda activate env/
4. Install Project Requirements
pip install -r requirements.txt
5. Environment Variables
Create a .env file and add the required key-value pairs:

GROQ_API_KEY = your_api_key
6. How to Run the Project
streamlit run app.py
Usage
Model & Persona Selection: Choose an AI model and persona from the sidebar.
Memory Configuration: Set how many previous messages the chatbot should remember.
Chat: Type your messages and engage with the assistant in real time.
Clear Chat & New Topics: Clear the chat history or start a new topic as needed.
View Stats: Check the sidebar for conversation stats.
