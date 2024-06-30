# Cine Db

## Description

A React-based web application that integrates Firebase for authentication and data storage, alongside fetching and displaying data from a third-party API. This project demonstrates secure user authentication and real-time data management through Firebase, combined with dynamic content rendering using React components.

Project hosted live: https://cine-db.vercel.app/

## Features

- **Firebase Authentication**: Secure user authentication using Firebase Authentication.
- **Firebase Firestore**: Store and manage application data in Firebase Firestore database.
- **Third-Party API Integration**: Fetch data from a third-party API and display it dynamically. [TMDB API](https://www.themoviedb.org)
- **React Components**: Modern React components for UI rendering and state management.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/shitu13/Cine-db.git

2. Install dependencies:

   ```bash
   npm install
   
3. Set up Firebase:
   - Create a Firebase project at Firebase Console.
   - Enable Authentication and Firestore in your Firebase project.
   - Add your Firebase configuration details to src/firebase/config.js.

4. Start the development server:

   ```bash
   npm run dev

## Demo User Interfaces
* UI for fetching movies from the database.
![Trending movies](src/images/UI-01.png)

* Saving movies and tv shows to your watchlist.
![Trending movies](src/images/UI-2.png)

* UI for showing details for specific movie.
![Trending movies](src/images/UI-3.png)

* Removing a movie from your watchlist.
![Trending movies](src/images/UI-4.png)



