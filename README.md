# WhatsApp GPT

A WhatsApp chatbot powered by GPT, built using Node.js, allowing users to interact with AI for various tasks like answering queries, generating text, and more.

## Features
- User Authentication (Optional)
- AI-Powered Chatbot (GPT Integration)
- Handle Text-Based Queries
- Support for Images & Media Responses
- Custom Command Handling
- Rate Limiting & Security Measures

## Tech Stack
- **Backend:** Node.js, Express.js
- **AI Model:** OpenAI GPT API
- **Database:** MongoDB/MySQL (Optional, for user tracking)
- **WhatsApp API:** Twilio, WhatsApp Web.js, or Meta WhatsApp Cloud API
- **Deployment:** AWS, Heroku, Vercel

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/opyash218/whats-app-Ai.git
   cd whatsapp-gpt
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   PORT=5000
   OPENAI_API_KEY=your_openai_api_key
   WHATSAPP_API_KEY=your_whatsapp_api_key
   JWT_SECRET=your_secret_key
   ```
4. Run the application:
   ```sh
   npm start
   ```
5. Connect to WhatsApp API & start chatbot.

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/auth/register | Register a new user (if applicable) |
| POST | /api/auth/login | User login (if applicable) |
| POST | /api/chat | Send a message to GPT |
| GET | /api/chat/history | Fetch chat history |

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

