# BarebonesSentimentChecker
This, is a barebones sentiment checker, which uses an application of Transformers.js. It checks if a statement is positive or negative with a certain level of certainty given as a percentage.

A simple browser-based sentiment analysis tool powered by [@xenova/transformers](https://www.npmjs.com/package/@xenova/transformers).  
This project demonstrates how to run Hugging Face models directly in the browser using JavaScript and WebAssembly.

---
<img width="1903" height="835" alt="image" src="https://github.com/user-attachments/assets/92e83e97-2766-4511-82c3-af876ff0de04" />
---
<img width="1908" height="835" alt="image" src="https://github.com/user-attachments/assets/bf0fbba7-f82f-4080-8959-0d5d344a8242" />



## Features
- Input text through a simple HTML form.
- Perform sentiment analysis (positive/negative) using DistilBERT fine-tuned on SST-2.
- Display label and confidence score.
- Runs entirely client-side — no backend or API calls required.

---

## Requirements
- Modern browser with ES Modules support (e.g., Chrome, Edge, Firefox, Safari).

- Local development server (e.g., `http-server`) to serve the HTML file.

---

## Installation
1. Clone or download this repository.
2. Install a simple static server if you don’t have one:
   ```bash
   npm install -g http-server
3. Start the server:
   ```bash
   http-server -p 3000
4. Open
   ```bash
   http://localhost:3000
in your browser.

