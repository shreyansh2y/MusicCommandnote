# Commonnote

**Find a feeling. Find a playlist. Find your sound.**

Commonnote is a responsive music discovery web app. Browse example playlists by mood and music category, save favorites in your browser, and open matching searches in Spotify or Apple Music.

> This is an independent project. It is not affiliated with Spotify, Apple, or any music label. Playlist names and collections in this demo are examples; listening buttons open searches in the selected music service.

## Features

- Search playlist names, moods, genres, and activities
- Explore by mood: Focus, Unwind, Energy, Feel good, or Explore
- Browse Bollywood, Indian, Hollywood, and International categories
- Save and remove playlists using browser storage
- Open matching music searches in Spotify or Apple Music
- Responsive layout for desktop and mobile
- No build tools, API keys, or server required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser.

You can also use a local static server or the VS Code Live Server extension while editing. This project uses plain HTML, CSS, and JavaScript.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow in `.github/workflows/pages.yml` that publishes the site when you push to the `main` branch.

1. Create a GitHub repository for this project.
2. Push the project files to the repository's `main` branch.
3. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
4. Open the **Actions** tab and wait for the Pages workflow to finish.
5. Your site URL will appear under **Settings → Pages**.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | Page structure and content |
| `styles.css` | Responsive visual design |
| `app.js` | Playlist data, filters, search, and saved playlists |
| `.github/workflows/pages.yml` | Automatic GitHub Pages deployment |
| `LICENSE` | MIT license; replace the name placeholder with your name |

## Make it yours

- Change the app name and page description in `index.html`.
- Add or edit playlist objects in the `playlists` array in `app.js`. Each playlist has a category, mood, genre, cover colors, search terms, and music-service links.
- Adjust colors, typography, and layout in `styles.css`.
- Replace the placeholder in `LICENSE` with your name or GitHub username.

## Current scope

Playlists are sample discovery entries. Spotify and Apple Music buttons open search results rather than playing audio inside this app. Saved playlists are stored in the current browser only; they are not synced between devices. Connecting real catalogs, previews, or accounts would require the relevant music-service APIs and their current terms.

## License

This project is available under the MIT License. See [LICENSE](LICENSE).
