# PDF Question-Answering Backend Service

## Introduction
A backend service that allows users to upload PDFs and ask questions in real-time through WebSocket communication.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   github clone https://github.com/sreemoyee-chakraborty/backend-service-of-a-pdf-document
   cd backend-service

### 3. Testing Script

- Include `test_backend.py` with all required tests.
- **Tests**: 
  - **PDF Upload Endpoint**: Tests for successful upload, handling invalid files, and checking response content.
  - **WebSocket Q&A**: Tests for connecting, sending questions, receiving answers, handling follow-up questions, and error responses.
  - **Rate Limiting**: Tests for rate-limiting enforcement on the `/upload` endpoint and WebSocket messages.
- **Running Tests**:
  - Add instructions in the README for running tests (`pytest test_backend.py`).
  - Ensure all test functions are self-contained and explain their purpose with comments.

### 4. Deployed Backend Link

- **Deployment Platform**: Choose a platform for deployment (e.g., **Heroku**, **AWS EC2**, or **DigitalOcean**).
  - For Heroku:
    - Use `requirements.txt` for dependencies.
    - Add a `Procfile` to run the FastAPI app (e.g., `web: uvicorn main:app --host=0.0.0.0 --port=${PORT}`).
  - Set environment variables for configuration (e.g., database URL, rate-limiting settings).
- **Link**: Once deployed, provide a public link to the backend in the README under a section titled **Deployed Backend Link**.

### 5. Demo Screencast

- **Recording Tool**: Use screen recording software (e.g., OBS Studio, Loom) to demonstrate the application.
- **Content**:
  1. **Intro**: Briefly describe what the demo will showcase.
  2. **PDF Upload**: Upload a PDF through the API and show the response.
  3. **WebSocket Q&A**:
     - Connect to the WebSocket endpoint.
     - Demonstrate asking initial and follow-up questions.
  4. **Rate Limiting**:
     - Send multiple requests to trigger rate limiting on `/upload`.
     - Similarly, send several WebSocket messages to show WebSocket rate-limiting in action.
  5. **Close**: Summarize the functionality.

- **Save & Link**: Save the video and upload it to a shareable platform like Google Drive or YouTube (unlisted). Include the link in the README under **Demo**.

---

By following these steps, you’ll meet each deliverable requirement comprehensively and ensure a clear, functional submission. Let me know if you need help with any specific part of the setup or coding!
