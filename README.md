# 🏛️ ރ. ދުވާފަރު މެޖިސްޓްރޭޓް ކޯޓް - ޑިޖިޓަލް ނޮޓިސް ބޯޑް

**R. Dhuvaafaru Magistrate Court - Digital Noticeboard**

A modern, responsive digital noticeboard system for the magistrate court with full Dhivehi language support.

## ✨ Features

- 📝 **Full Dhivehi Language Support** - Complete interface in Dhivehi (ދިވެހި)
- 🖼️ **Media Gallery** - Upload and display photos and videos
- ⚖️ **Case Schedule** - Today's court case schedule with status tracking
- 📢 **Announcement Ticker** - Scrolling announcements at the bottom
- 🎨 **Multiple Font Options** - Switch between Noto Sans Thaana, MV Waheed, and Faruma
- 🕐 **Maldives Time** - Automatic local time display
- 📱 **Responsive Design** - Works on all screen sizes

## 🚀 Quick Start

### Option 1: Direct Use (No Installation)
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start using immediately!

### Option 2: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → "main" → "/ (root)"
4. Your noticeboard will be live at `https://yourusername.github.io/dhivehi-noticeboard/`

## 🔤 Font Setup

The app includes three font options:

1. **Noto Sans Thaana** (Default) - Google Fonts, works immediately
2. **MV Waheed** - Traditional Dhivehi font
3. **Faruma** - Modern Dhivehi font

### To use MV Waheed or Faruma:

1. Download the font files:
   - **MV Waheed**: https://www.thaanafontgallery.com/font/mv-a-waheed/
   - **Faruma**: https://raajjefonts.github.io/

2. Place the font files in the `/fonts` folder:
   ```
   fonts/
   ├── MV_Waheed.otf (or .ttf)
   └── Faruma.otf (or .ttf)
   ```

3. The font toggle buttons will automatically work!

## 📁 Project Structure

```
dhivehi-noticeboard/
├── index.html          # Main application file
├── fonts/              # Dhivehi font files (add your own)
│   └── README.md       # Font setup instructions
├── README.md           # This file
├── LICENSE             # License file
└── .gitignore          # Git ignore file
```

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `index.html`:
```css
:root {
    --primary: #1e3a5f;    /* Main blue color */
    --secondary: #c9a227;  /* Gold accent */
    --accent: #2d5a87;     /* Light blue */
    --bg-dark: #0f172a;    /* Background */
}
```

### Adding Default Announcements
Edit the ticker items in the HTML:
```html
<div class="ticker-track" id="tickerTrack">
    <span class="ticker-item">Your announcement here</span>
</div>
```

## 🌐 Browser Support

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

<p align="center">
  <strong>ރ. ދުވާފަރު މެޖިސްޓްރޭޓް ކޯޓް</strong><br>
  R. Dhuvaafaru Magistrate Court
</p>
