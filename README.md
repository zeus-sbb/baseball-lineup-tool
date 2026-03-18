# ⚾ Baseball Lineup Tool

An interactive web application for managing baseball team lineups with drag-and-drop player positioning.

## Features

- **Player Management** — Add team player names
- **Interactive Field** — Drag-and-drop players to field positions
- **Multi-Inning Support** — Manage lineups for multiple innings
- **Smart Carry-Over** — Players stay in their positions for the next inning unless changed
- **PDF Export** — Generate printable lineup cards for the dugout
- **Mobile-Friendly** — Works on phones, tablets, and computers
- **Browser-Based** — No installation needed, no server required

## How to Use

1. **Enter Team Info** — Add team name, coach name, and player list
2. **Set Innings** — Choose how many innings the game will have
3. **Position Players** — Drag player names onto the field positions
4. **Navigate Innings** — Use Next/Previous to move between innings
5. **Export PDF** — Click "Export to PDF" to get a printable lineup card

## Deployment

This tool is deployed to GitHub Pages at: [your-github-pages-url]

### Embedding in Squarespace

Add this iframe code to your Squarespace page:

```html
<iframe 
    src="https://zeus-sbb.github.io/baseball-lineup-tool/" 
    width="100%" 
    height="800" 
    style="border: none; border-radius: 8px;">
</iframe>
```

## Technology

- **Frontend:** HTML5, CSS3, JavaScript (vanilla, no dependencies)
- **PDF Generation:** html2pdf.js library
- **Hosting:** GitHub Pages (free, always available)
- **Browser Storage:** Data stored locally in your browser (private)

## Roadmap

- [ ] Save lineups to browser (localStorage)
- [ ] Export as image
- [ ] Email lineups
- [ ] Team roster management
- [ ] Game statistics tracking

## License

Private - For authorized use only

---

Built with ⚾ by Zeus for the Athletics CVLL
