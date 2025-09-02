# Trial of Knowledge: The Magic Quiz
# The App
You can play *Trial of Knowledge* at the website hosted on GitHub pages: <https://multimeric.github.io/MagicQuiz/>

# Contributing

If you want to help improve *Trial of Knowledge*, feel free to fork this repository and create a pull request. If you're not sure what needs work, have a look at the [issues page](https://github.com/multimeric/MagicQuiz/issues). Even if there is nothing currently wrong with the application, feel free to contribute more preset quizzes (add some more entries in `src/presets.js`).

## Technologies
*Trial of Knowledge* is written in JavaScript (ES2016). The application uses ReactJS in combination with MobX to create the user interface and manage state.

## Repository Structure
Almost everything relevant is inside the `src` directory:

* `src/components`: The React components that make up the GUI
* `src/img`: The images used by the application, particularly magic icons and mana icons
* `src/models`: Any classes that are used throughout the application
* `src/stores`: MobX stores that manage the application state
* `src/index.js`: The application entry point. The JavaScript bundle is built starting from this file
* `src/metadata.js`: App metadata such as its title and subtitle
* `src/presets.js`: A large array of preset quizzes (Scryfall searches with descriptions of each)
