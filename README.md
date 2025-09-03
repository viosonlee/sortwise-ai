# SortWise AI

SortWise AI is a smart garbage sorting assistant for Nishinomiya City, Japan. It uses Google's Gemini AI to help you determine the correct garbage category for any item, based on the latest local regulations.

## Features

*   **AI-Powered Sorting:** Simply type the name of an item or upload a picture, and the AI will identify the correct garbage category.
*   **Multi-Language Support:** The application is available in English, Japanese, and Chinese.
*   **Detailed Instructions:** Get clear, step-by-step instructions on how to prepare your items for disposal.
*   **Easy to Use:** A simple and intuitive interface makes garbage sorting a breeze.

## Tech Stack

*   **Frontend:** React, Vite, Tailwind CSS
*   **AI:** Google Gemini

## Getting Started

To run the project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/ho_ri/sortwise-ai.git
    cd sortwise-ai
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Set up your API key:**

    *   Get a free API key from [Google AI Studio](https://aistudio.google.com/).
    *   When you first launch the application, you will be prompted to enter your API key.

4.  **Run the development server:**

    ```bash
    npm run dev
    ```

    The application will be available at `http://localhost:5173`.

## How to Use

1.  Enter the name of an item in the text input field, or click the image upload area to select a picture of the item.
2.  Click the "Sort Item" button.
3.  The AI will analyze the item and display the correct garbage category, along with preparation instructions.

## Deployment

The application is configured for deployment to GitHub Pages. To deploy the application, run the following command:

```bash
npm run deploy
```

This will build the application and deploy it to the `gh-pages` branch of your repository.
