# My First React App

This is a simple React application that allows users to search for movies using the OMDB API. The app displays a list of movies based on the search term entered by the user.

## Features

- Search for movies by title
- Display a list of movies with their details
- Show a message when no movies are found

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Node.js and npm installed on your machine

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/my-first-react-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd my-first-react-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the App

1. Start the development server:
   ```bash
   npm start
   ```
2. Open your browser and go to `http://localhost:3000` to see the app in action.

## Project Structure

- `src/App.js`: The main component that handles the search functionality and displays the movies.
- `src/MovieCard.js`: A component that displays individual movie details.
- `src/App.css`: The stylesheet for the app.
- `src/search.svg`: The search icon used in the app.

## API

This project uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. You will need an API key to use the OMDB API. Replace the `API_URL` in `src/App.js` with your own API key.

## License

This project is licensed under the MIT License.
