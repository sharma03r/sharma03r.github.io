# Marvel App

This project is a web-based SuperHero portal that utilizes JavaScript, CSS, and HTML to fetch and display a list of superheroes using the Marvel API. It provides functionalities such as displaying a list of superheroes, filtering based on search queries, favoriting superheroes, and displaying detailed information about a selected superhero.

## Features

### Home Page

- **Superhero List:** Display a list of superheroes retrieved from the Marvel API.
- **Search Bar:** Filter superheroes based on the search query.
- **Favorite Button:** Add superheroes to "My Favorite Superheroes" list by clicking on the favorite button next to each search result.

### Superhero Page

- Display detailed information about a selected superhero, including their name, photo, bio, and additional data obtained from the Marvel API (comics, events, series, stories, etc).

### My Favorite Superheroes Page

- Display a list of all favorited superheroes.
- **Persistent List:** The list of favorite superheroes is persistent, maintaining the same superheroes even after closing the browser.
- **Remove from Favorites Button:** Each superhero in the favorites list has a "Remove from Favorites" button, allowing users to remove selected superheroes from the list.

## API Endpoint

- The project uses the Marvel API to retrieve superhero data. The API endpoint used for fetching superhero information is:
https://gateway.marvel.com:443/v1/public/characters?ts=<time-stamp>&apikey=<public-key>&hash=<md5(ts+privateKey+publicKey)>

Replace `<time-stamp>`, `<public-key>`, and `<md5(ts+privateKey+publicKey)>` with the appropriate values from the Marvel API to access superhero data.

## How to Use

1. Clone the repository from GitHub.
2. Obtain access to the Marvel API and replace the placeholder values in the API endpoint with your actual API credentials.
3. Open the `index.html` file in a web browser to access the SuperHero portal.

## Contributors

- [Rahul Sharma](https://github.com/sharma03r) - Developer
