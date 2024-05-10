# Movie Ratings Flask Application

This Flask-based application allows users to manage a list of their favorite movies, including the ability to rate, review, and update details. The application fetches movie information from The Movie Database (TMDB) API and supports CRUD operations using SQLAlchemy with SQLite as the database.

## Project Structure

The project is divided into several components including Python scripts, HTML templates, and CSS files. Below is an outline of the major components:

- **`main.py`**: Contains the Flask application setup, routes, database configuration, and business logic.
- **`templates/`**: Folder containing HTML files for rendering views.
- **`static/css/`**: Folder containing custom CSS files for styling.
- **`instance/`**: Folder containing SQLITE database file for storing the data.

## Features

- **Home Page**: Displays a list of movies ranked by user ratings.
- **Add Movie**: Search and add movies from TMDB to your database.
- **Rate Movie**: Update the rating and review for a specific movie.
- **Delete Movie**: Remove a movie from your list.

## Installation and Setup

To set up and run the project locally, follow these steps:

### Prerequisites

Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Clone the Repository

```bash
git clone https://github.com/sarvesh-2109/movie-ratings.git
cd movie-ratings
```

### Install Required Packages

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file in the project root directory and add your TMDB API key:

```plaintext
MOVIE_DB_API_KEY=your_api_key_here
```

### Run the Application

Start the Flask application with the following command:

```bash
python main.py
```

Navigate to `http://127.0.0.1:5000/` in your web browser to view the application.

## Usage

- **View All Movies**: The homepage (`/`) displays all the movies in the database, ranked by user ratings.
- **Add a Movie**: Navigate to `/add` to search and add movies via the TMDB API.
- **Edit Movie Rating**: Click on the `Update` link next to any movie to edit its rating and review.
- **Delete a Movie**: Click the `Delete` link to remove a movie from the database.

## Contributing

Contributions to the project are welcome. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

