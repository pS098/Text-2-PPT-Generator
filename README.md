# Text-2-PPT-Generator
“Convert text, notes, or markdown into professional PowerPoint presentations automatically. Add guidance, use AI models like GPT, Claude, or Gemini, and optionally apply a PowerPoint template to generate slides ready for download in seconds.”
Text to PowerPoint Generator

Convert text, notes, or markdown into professional PowerPoint presentations automatically using AI.

Description

This web application allows users to transform raw text into structured PowerPoint presentations in seconds. Users can provide optional guidance, select an AI provider (OpenAI GPT, Claude, or Gemini), and optionally upload a PowerPoint template to style the output slides. The generated .pptx file is ready for download immediately.

Features

Convert plain text, markdown, or notes into slides.

Optional guidance to control presentation style (e.g., technical, investor pitch).

Support for multiple LLM providers:

OpenAI (GPT)

Anthropic (Claude)

Google (Gemini)

Upload custom PowerPoint templates (.pptx or .potx) for consistent slide design.

Automatically download generated presentations.

Responsive, user-friendly interface.

Demo


Screenshot showing the form and output preview.

Getting Started
Prerequisites

Modern web browser (Chrome, Edge, Firefox)

API key from your LLM provider (OpenAI, Anthropic, Google)

Optional: PowerPoint template file

Installation

Clone the repository:

git clone https://github.com/yourusername/text-to-powerpoint.git
cd text-to-powerpoint


Open index.html in your browser.

Enter your text, select LLM provider, paste your API key, optionally upload a template, and click Generate Presentation.

Usage

Text Input – Paste your content or markdown.

Guidance (Optional) – Specify style or focus of slides.

LLM Provider – Choose your AI model provider.

API Key – Provide API key for the selected AI provider.

Template File (Optional) – Upload .pptx or .potx to style slides.

Filename – Set the output presentation name.

Generate – Click the button to create and download your PowerPoint.

Folder Structure
text-to-powerpoint/
├── index.html          # Frontend web application
├── styles.css          # Optional separate CSS
├── script.js           # Optional separate JS
├── README.md           # Project README
└── demo_screenshot.png # Demo screenshot for README

Tech Stack

Frontend: HTML5, CSS3, JavaScript (vanilla)

Backend (API): AI-based text to slide generator (external API service)

AI Models Supported: OpenAI GPT, Anthropic Claude, Google Gemini

Contributing

Contributions are welcome! Feel free to:

Improve the UI/UX

Add more LLM providers

Optimize performance

Add new features like slide preview

Fork the repo

Create a new branch

Commit your changes

Submit a pull request

License

This project is licensed under the MIT License – see the LICENSE
 file for details.

Acknowledgements

OpenAI

Anthropic

Google Gemini
