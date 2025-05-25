# Cerebras-Hackathon Agent
deployed here : https://g.co/gemini/share/0518e4824b0b



Qwen Agent 🤖
A versatile web-based chatbot application that allows users to interact with different AI models for various tasks, all within a sleek, natural dark mode interface.

✨ Features
Chat with Qwen 32b: Engage in conversational chat with the Qwen 32b model, powered by the OpenRouter API.

Generate Images: Create stunning static images from your text prompts using the Google Imagen API. Simply select "Generate Image" mode and describe what you want to see!

Summarize Text: Get concise summaries of any text you provide, leveraging the power of the Google Gemini API. Switch to "Summarize Text" mode and paste your content.

Dynamic Mode Selection: Easily switch between different functionalities using a convenient dropdown menu.

Intuitive UI: A modern, natural dark mode theme with responsive design ensures a comfortable user experience across various devices.

Contextual Guidance: The input field's placeholder text and the chatbot's greeting message dynamically update to guide you based on the selected mode.

🚀 How to Use
Save the Code: Save the entire HTML code provided as a single .html file (e.g., index.html) on your computer.

Open in Browser: Open the saved .html file in a modern web browser (Google Chrome is recommended for optimal compatibility).

Select a Mode: Use the "Select Mode" dropdown at the top of the interface to choose your desired functionality:

"Chat with Qwen 32b"

"Generate Image"

"Summarize Text"

Enter Your Input: Type your message or prompt into the text area at the bottom. The placeholder text will change to guide you on what to enter for the selected mode.

Send Message: Click the "Send Message" button or press Enter (without Shift) to submit your request.

View Results: The chatbot's response, whether it's a chat reply, a generated image, or a text summary, will appear in the chat history. Generated images will include a "Download Image" button for easy saving.

🛠️ Technologies Used
HTML5: For the core structure of the web application.

CSS (Tailwind CSS): For rapid and responsive styling, providing the dark mode aesthetic.

JavaScript: For all interactive elements, API calls, and dynamic content updates.

OpenRouter API: Connects to the Cerebras provider for the Qwen 32b chat model.

Google Imagen API (imagen-3.0-generate-002): Powers the image generation feature.

Google Gemini API (gemini-2.0-flash): Used for text summarization.

⚠️ Limitations
No Persistent History: Chat history is not saved; it will clear upon page refresh.

Client-Side Only: This is a purely client-side application. All API calls are made directly from your browser.

Animated GIF Generation: While initially explored, direct animated GIF generation within this client-side setup proved challenging due to browser and API limitations for multi-frame streaming and complex encoding. The /image command now generates static images.

Website Content Fetching: Directly fetching and summarizing content from arbitrary external websites (via a URL) is not supported in this client-side setup due to browser security policies (CORS). The "Summarize Text" mode requires you to paste the text directly.
