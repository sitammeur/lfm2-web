# LFM-2 Web 🤖

This is a simple web app that demonstrates how to use the [LFM2-350M](https://huggingface.co/onnx-community/LFM2-350M-ONNX) model in the browser using [Transformers.js](https://huggingface.co/docs/transformers.js) and ONNX Runtime Web. The application allows users to chat with the LFM2-350M model and receive real-time responses.

## Project Structure

The project is structured as follows:

- `assets/`: This directory contains screenshots of the end application.

- `public/`: Static assets like images, icons, and fonts.

- `src/`: Core source code for the application.

  - `components/`: Reusable React components for the application.

    - `icons/`: Icon components for the application.

      - `ArrowRightIcon.jsx`: Arrow right icon component.
      - `BotIcon.jsx`: Bot icon component.
      - `StopIcon.jsx`: Stop icon component.
      - `UserIcon.jsx`: User icon component.

    - `Chat.jsx`: Chat component for displaying chat messages.
    - `Progress.jsx`: Progress component for displaying progress bar.

  - `styles/`: CSS files for styling the application.

    - `index.css`: Global CSS styles for the application.
    - `Chat.css`: CSS styles for the chat interface.

  - `worker.js`: Transformers.js worker for running the Qwen model.
  - `App.jsx`: Main React component for the application.
  - `main.jsx`: Entry point for the application.

- `.gitignore`: Specifies which files and directories should be ignored by Git.
- `LICENSE`: Project licensing information.
- `README.md`: Project documentation and setup instructions.
- `index.html`: Main HTML file for the application.
- `package.json`: Project dependencies and script configuration.
- `tailwind.config.js`: Tailwind CSS configuration file.
- `vite.config.js`: Vite configuration file for the project.

## Technologies Used

- **HTML**: Standard markup language for creating web pages.
- **Tailwind CSS**: Utility-first CSS framework for styling web applications.
- **JavaScript**: High-level programming language for building web applications.
- **React**: JavaScript library for building user interfaces.
- **Transformers.js**: JavaScript library for running Hugging Face models in the browser.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository: `git clone https://github.com/sitamgithub-MSIT/qwen-web.git`
2. Change the directory: `cd qwen-web`
3. Install the required dependencies: `npm install`
4. Run the application: `npm run dev`

Open your local host to view the web application in your browser at `http://localhost:5173/`. You can also access a live version of the application [here](https://qwen-web.vercel.app/), which is deployed on Vercel.

## Results

The application allows users to chat with LFM2-350M, a large language model, that operates within web browsers via 🤗 Transformers.js and ONNX Runtime Web.

**Note**: To see results, please refer to the `assets` folder in the repository.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please raise an issue to discuss the changes you would like to make. Once the changes are approved, you can create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions regarding the project, feel free to reach out to me on my GitHub profile.

Happy coding! 🚀
