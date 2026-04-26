# Blog with Chess Game

A simple, elegant blog platform with an interactive chess game built with HTML, CSS, and JavaScript.

## Features

### Blog (index.html)
- **Write Posts**: Create new blog posts with a title, category, and body content
- **Organize Content**: Categorize posts as Essays, Observations, Notes, Journal entries, or Other
- **Word Counter**: Live word count while writing posts
- **Simple Navigation**: Easy-to-use interface with Home, Write, and About sections
- **Local Storage**: Posts are saved in the browser

### Chess Game (chess.html)
- **Interactive Chess**: Full chess game with piece movement and captures
- **Multiple Game Modes**: Choose between different gameplay options
- **Beautiful UI**: Dark theme with elegant typography and smooth animations
- **Move Validation**: Proper chess rules enforcement
- **Visual Feedback**: Highlighted squares show available moves, last moves, and check status

## Project Structure

```
blog/
├── index.html      # Main blog application
├── chess.html      # Interactive chess game
└── README.md       # This file
```

## Getting Started

1. Open `index.html` in a web browser to access the blog
2. Click on "Write New Post" to create your first post
3. Visit `chess.html` to play chess

## Usage

### Blog
- **Home**: View all your posts
- **Write New Post**: Create a new blog entry with title, category, and content
- **About**: Learn more about the blog (customize this section as needed)

### Chess
- Select a game mode from the menu
- Click on pieces to select them and highlight available moves
- Click on highlighted squares to move pieces
- The game enforces standard chess rules

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (no dependencies)

## Styling

The chess game features a sophisticated dark theme with:
- Custom color palette with warm accents
- Responsive design that works on desktop and mobile
- Smooth animations and transitions
- Professional typography using Google Fonts

## Browser Compatibility

Works on all modern browsers that support:
- HTML5
- CSS3 Grid and Flexbox
- ES6 JavaScript

## Notes

- Posts are stored in browser local storage
- No server required - runs entirely in the browser
- Data persists between sessions (as long as browser storage isn't cleared)

## Future Enhancements

- Export posts as files
- Post search and filtering
- Chess game replay and move history
- Post timestamps and edit history
