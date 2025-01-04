
# Virtual Learning Assistant

A virtual learning assistant web application that uses AI to solve math problems by analyzing text from a live camera feed. It captures the problem, processes it, and provides a step-by-step solution with text-to-speech capabilities.

---

## Features

- **Live Camera Feed**: Supports both front and back camera usage.
- **OCR (Text Recognition)**: Extracts text from images using Tesseract.js.
- **Problem Solving**: Solves basic math problems, including arithmetic and equations.
- **Text-to-Speech**: Reads the solution aloud using the Web Speech API.
- **Flash and Zoom Controls**: Provides flash toggle and zoom adjustments.
- **History Management**: Saves the last five solved problems and allows exporting the history.

---

## How It Works

1. Access the camera to capture the problem.
2. Process the captured image using OCR to extract text.
3. Solve the extracted problem (currently supports basic math).
4. Display the solution step-by-step and dictate it using text-to-speech.
5. Store solutions in history for future reference.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/virtual-learning-assistant.git
   ```
2. Navigate to the project directory:
   ```bash
   cd virtual-learning-assistant
   ```
3. Open the `index.html` file in a browser:
   - You need to serve it via HTTPS to access the camera.
   - Use a local web server like Python's built-in server:
     ```bash
     python -m http.server 8000
     ```
   - Or use Node.js:
     ```bash
     npx http-server
     ```
4. Open the link (e.g., `http://localhost:8000`) in your browser.

---

## Deployment

Demo Link :- https://pranshuguptaa.github.io/Virtual-Learning-Assistant/

You can deploy the project using any of the following platforms:

- **GitHub Pages**:
  1. Push your code to a GitHub repository.
  2. Go to the repository settings > Pages > Enable GitHub Pages.
  3. Your site will be live at: `https://[username].github.io/[repository-name]`.

- **Netlify**:
  1. Sign up at [Netlify](https://netlify.com).
  2. Drag and drop your project folder into Netlify.
  3. Your site will be live at: `https://[site-name].netlify.app`.

- **Vercel**:
  1. Sign up at [Vercel](https://vercel.com).
  2. Connect your GitHub repository.
  3. Deploy and get a link like: `https://[project-name].vercel.app`.

---

## Usage Instructions

1. Open the deployed application in a browser (HTTPS required).
2. Grant camera permissions when prompted.
3. Point the camera at a printed or typed math problem.
4. Click "Analyze Problem" to get the solution.
5. Use additional features like flash, zoom, and history as needed.

---

## Tech Stack

- **HTML5**: Structuring the application.
- **JavaScript**: Core logic and features.
- **Tesseract.js**: For OCR (text recognition).
- **Web Speech API**: For text-to-speech functionality.
- **CSS**: Styling and responsive design.

---

## Limitations

- Works best with printed text.
- Requires good lighting for accurate OCR.
- Supports only basic math problems in the current version.

---

## Future Enhancements

- Add support for handwritten text recognition.
- Expand to solve more complex problem types.
- Improve the history management system.
- Enhance the UI with better animations and features.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For queries or suggestions, feel free to reach out to [pranshuggupta768@gmail.com].
```
