# Music Player

A modern, web-based music player built with React that provides an intuitive interface for playing and managing your music collection.

## Features

- 🎵 **Music Playback** - Play, pause, and navigate through your music collection
- ⏭️ **Track Navigation** - Skip to next/previous tracks with ease
- 📊 **Progress Tracking** - Visual progress bar with current time and duration display
- 🎼 **Song Library** - Browse and select from a curated collection of tracks
- 🔄 **Auto-play Next** - Automatically plays the next track when current song ends
- 🎨 **Clean UI** - Simple and intuitive user interface

## Technology Stack

- **React** - Frontend framework
- **React Router** - Navigation and routing
- **Howler.js** - Audio playback engine
- **Create React App** - Build tooling and development setup

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/robertbiv/music_player.git
cd music_player
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Available Scripts

### `npm start`

Runs the app in development mode.\
The page will reload when you make changes, and lint errors will appear in the console.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.\
The build is optimized for best performance, with minified files and hashed filenames.

## Project Structure

```
music_player/
├── public/          # Static files
├── src/
│   ├── components/  # Reusable components (NavBar, PlayerContext)
│   ├── Music/       # Audio files
│   ├── App.js       # Main application component
│   ├── MusicPlayer.js  # Music player component with controls
│   ├── Songs.js     # Song list component
│   └── index.js     # Application entry point
└── package.json
```

## Usage

1. **Browse Songs**: Navigate to the songs page to see all available tracks
2. **Select a Track**: Click on any song to load it into the player
3. **Control Playback**: Use the Play/Stop button to control playback
4. **Navigate Tracks**: Use Next/Previous buttons to move between songs
5. **Monitor Progress**: Watch the progress bar and time indicators to track playback

## Music Collection

The player comes with a curated collection of tracks including:
- Hyperfun
- Magic Forest
- Neon Laser Horizon
- River Flute
- Soaring
- Split In Synapse
- The Entertainer
- Volatile Reaction
- Wagon Wheel

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
