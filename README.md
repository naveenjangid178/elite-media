# YouTube Clone using React and RapidAPI

This project is a **YouTube clone** built using **React.js** and **RapidAPI**, designed to replicate core YouTube features such as video search, playback, and viewing video details. The app fetches data dynamically from the **RapidAPI YouTube API**, eliminating the need for CRUD operations and focusing purely on content retrieval and presentation.

## Key Features

- **Search Functionality**: Search for YouTube videos based on keywords or phrases, similar to the YouTube search bar.
- **Video Playback**: Watch selected videos directly in the app, embedded with an external player (YouTube player).
- **Video Details**: Display detailed information for each video, including title, description, view count, upload date, and channel info.
- **Responsive Design**: Fully responsive layout, optimized for desktop, tablet, and mobile devices.
- **API Integration**: Fetch video data dynamically using the **RapidAPI YouTube API**.

## Tech Stack

- **Frontend**: React.js, React Router, Axios (for API calls), CSS
- **API**: [RapidAPI YouTube v3 API](https://rapidapi.com/ytdlfree/api/youtube-v31)
- **State Management**: React hooks (`useState`, `useEffect`)

## Installation & Setup

To run this project locally, follow the steps below:

### 1. Clone the Repository

```bash
git clone https://https://github.com/naveenjangid178/elite-media
```
### 2.Navigate to the Project Folder
```bash
cd youtube-clone-react
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Set Up API Key
   Create a .env file in the root directory of the project and add your RapidAPI YouTube API key:
   ```plaintext
   VITE_APP_RAPID_API_KEY=your_rapidapi_key_here
   ```
   You can obtain the API key by signing up for RapidAPI and subscribing to the YouTube API.

### 5. Run the Development Server
   ```bash
   npm run dev
