# Real-Time Phishing Detection System – Frontend

## Major Project

### Project Overview

The frontend component of a Real-Time Phishing Detection System developed as a major project. It provides a user-friendly web interface that allows users to submit website URLs and view their phishing detection results.

The frontend communicates with a machine learning-based backend API to analyze submitted URLs and display the prediction results.

## Features

- User-friendly interface for URL submission.
- Integration with the phishing detection API.
- Display of phishing detection results.
- Interactive interface using JavaScript.
- Responsive web design.
- Real-time communication with the backend service.

## Technologies Used

- **HTML5** – Structure of the web application.
- **CSS3** – Styling and responsive design.
- **JavaScript** – Frontend functionality and API communication.

## Project Structure

```text
phishing-detector-frontend/
│
├── index.html
├── style.css
├── script.js
├── wrangler.jsonc
└── .gitignore
```

## System Integration

This frontend is one of the components of the larger phishing detection system.

- **Backend:** FastAPI-based REST API.
- **Machine Learning:** XGBoost-based phishing URL classification.
- **Frontend:** Web-based interface for user interaction.

## How It Works

1. The user enters a website URL.
2. The frontend sends the URL to the backend API.
3. The machine learning model analyzes the URL.
4. The API returns the prediction.
5. The frontend displays the detection result.

## Running the Project

1. Clone or download this repository.
2. Open the project folder.
3. Run the frontend using a local development server, such as VS Code Live Server.
4. Ensure the backend API is accessible and correctly configured in `script.js`.
5. Open the application in your browser and test a URL.

## Project Information

- **Project Title:** Real-Time Phishing Detection System Using Machine Learning
- **Project Type:** Major Project
- **Component:** Frontend Development
- **Domain:** Machine Learning and Cybersecurity

## Related Repositories

- Backend API: [https://github.com/rkm1131/phishing-detection-api](https://github.com/rkm1131/phishing-detection-api)
- Browser Extension: [https://github.com/rkm1131/phishing-detector-extension](https://github.com/rkm1131/phishing-detector-extension)

---

Developed as part of a B.Tech major academic project.
