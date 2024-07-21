# Human Sense Ads

## Overview

Human Sense Ads is a project designed to detect humans, extract their features, and generate personalized messages using a language model (LLM) to grab their attention towards advertisements displayed on a screen. The project is divided into three main parts:

1. **Cronjob**: Detects humans and creates messages based on their features.
2. **Backend**: Receives messages and signals the frontend upon state change.
3. **Frontend**: Displays the generated messages to the users.

## Project Structure

- **cronjob/**: Contains the main script (`main.py`) for detecting humans and creating messages.
- **backend/**: Contains the Express.js server code.
- **frontend/**: Contains the React.js application code.

## Getting Started

### Prerequisites

- Python and pip installed on your machine.
- Node.js and npm installed on your machine.

### Setting Up the Cronjob

```bash
cd cronjob
python main.py
```

### Setting Up the Backend

```bash
cd backend
npm install
node server.js
```
The backend should now be running and ready to receive POST requests on http://localhost:5000.

### Setting Up the Frontend

```bash
cd frontend
npm install
npm start
```
The frontend should now be running on http://localhost:3000.

### Using the Application

- Ensure the cronjob script is running to detect humans and create messages.
- The generated message will be sent to the backend as a POST request.
- The backend stores the message and signals the frontend upon state change.
- The frontend displays the generated message to the users, grabbing their attention towards the advertisement.

### Contributing

Feel free to contribute to this project by submitting issues or pull requests. Contributions are welcome!

### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments

- React
- Express.js
- Node.js
- Llama3
