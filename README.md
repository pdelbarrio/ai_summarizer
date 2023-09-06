# Summarify - AI Article Summarization Web Application

Summarify is a responsive web application built with React that leverages the power of AI to summarize articles and web content. This project was developed for practicing various skills, including setting up a ReactJS project with Vite, creating a responsive UI with Tailwind CSS, making advanced API requests using the Article Extractor and Summarizer API from RapidAPI, handling form events, using Redux Toolkit, and more.

## Features

- **ReactJS with Vite**: The project is built using React with Vite, a fast development tool that simplifies project setup.

- **Tailwind CSS**: The UI/UX of the application is designed using Tailwind CSS, making it responsive and visually appealing.

- **Article Summarization**: Summarify utilizes AI from the [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer) to generate concise and coherent summaries of articles provided as input.

- **API Integration**: The application integrates with the Article Extractor and Summarizer API from RapidAPI. You will need to obtain an API key from RapidAPI for this purpose.

- **Form Event Handling**: The application handles user input and form events gracefully, ensuring a smooth user experience.

- **Redux Toolkit**: Redux Toolkit is used to make advanced RTK query API requests that fire conditionally, enhancing the application's efficiency and responsiveness.

- **Deployment**: The application is deployed and can be accessed at [Summarify](https://summarify-app.netlify.app/). Please note that the free plan on RapidAPI is limited to 50 requests per month.

- **Clean Code**: The codebase follows best practices for maintainability and readability, making it easy to understand and extend.

## Usage

1- Enter the URL of the article you want to summarize in the input field and press Enter.

2- The AI will process the article and generate a summary, displaying it on the screen.

3- The application will save the summaries with their links in localstorage in case you want to retrieve them without having to call the API again.

4- You can also retrieve the links by copying them to clipboard with a single click.