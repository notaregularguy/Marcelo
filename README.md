# Marcelo ⚡

A beautiful, modern markdown editor with live preview and syntax highlighting. Built with pure HTML, CSS, and JavaScript.

![Marcelo Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Marcelo+Markdown+Editor)

## ✨ Features

- **Live Preview** - See your markdown rendered in real-time as you type
- **Syntax Highlighting** - Code blocks beautifully highlighted with Highlight.js
- **GitHub Flavored Markdown** - Full GFM support including tables and task lists
- **Elegant Design** - Glass-morphism UI with smooth animations and gradients
- **Mobile Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Task Lists** - Interactive checkboxes for todo lists and project management
- **Code Support** - Syntax highlighting for 190+ programming languages
- **Smart Typography** - Automatic quote conversion and list formatting
- **Synchronized Scrolling** - Editor and preview scroll together seamlessly
- **Quick Actions** - Toolbar buttons for common formatting options

## 🚀 Demo

Try Marcelo online: **[https://brown-gusta-90.tiiny.site](https://brown-gusta-90.tiiny.site)**

## 📋 Supported Markdown Features

### Text Formatting
- **Bold** and *italic* text
- ~~Strikethrough~~ text
- ==Highlighted== text
- `Inline code` snippets
- Superscript^2^ and subscript~1~

### Lists and Tasks
- [x] Completed tasks
- [ ] Incomplete tasks
- Bulleted lists
- Numbered lists
- Nested lists

### Code Blocks
```javascript
// Syntax highlighting for 190+ languages
const hello = 'world';
console.log(`Hello, ${hello}!`);
```

### Tables
| Feature | Status | Priority |
|---------|--------|----------|
| Live Preview | ✅ | High |
| Syntax Highlighting | ✅ | High |
| Mobile Support | ✅ | Medium |

### Other Features
- > Blockquotes with multiple lines
- Horizontal rules
- Links and images
- Headers (H1-H6)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with flexbox, gradients, and backdrop filters
- **JavaScript ES6+** - Core functionality and DOM manipulation
- **Marked.js** - Markdown to HTML conversion
- **Highlight.js** - Syntax highlighting for code blocks

## 📦 Installation

### Option 1: Direct Download
1. Download the HTML file
2. Open in any modern web browser
3. Start writing markdown immediately

### Option 2: Local Development
```bash
# Clone or download the project
git clone <repository-url>
cd marcelo

# Open with a local server (recommended)
python -m http.server 8000
# or
npx serve .

# Open http://localhost:8000 in your browser
```

### Option 3: Deploy Anywhere
The editor is a single HTML file with no dependencies. Deploy to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## 🎨 Customization

### Changing the Theme
Modify the CSS variables in the `<style>` section:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --accent-color: #667eea;
  --text-color: #e1e1e1;
}
```

### Adding New Toolbar Buttons
```javascript
// Add to the toolbar section in HTML
<button class="btn" onclick="insertText('### ')">H3</button>

// The insertText function handles insertion at cursor position
```

### Syntax Highlighting Themes
Replace the Highlight.js theme CSS link:
```html
<!-- GitHub Dark (default) -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.min.css">

<!-- Other popular themes -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/atom-one-dark.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/dracula.min.css">
```

## 🚀 Usage Examples

### Writing Documentation
Perfect for creating README files, API documentation, and project wikis.

### Note Taking
Ideal for technical notes, meeting minutes, and knowledge management.

### Blog Writing
Great for drafting blog posts with live preview of formatting.

### Educational Content
Excellent for creating tutorials, course materials, and study guides.

## 📱 Browser Compatibility

Marcelo works on all modern browsers:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Here are some ways to help:

1. **Bug Reports** - Found an issue? Open an issue with details
2. **Feature Requests** - Have an idea? We'd love to hear it
3. **Code Contributions** - Submit pull requests for improvements
4. **Documentation** - Help improve this README or add examples

### Development Setup
1. Fork the repository
2. Make your changes to the HTML file
3. Test in multiple browsers
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the details below:

```
MIT License

Copyright (c) 2024 Marcelo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Acknowledgments

- **[Marked.js](https://marked.js.org/)** - Fast markdown parser and compiler
- **[Highlight.js](https://highlightjs.org/)** - Syntax highlighting for the web
- **Design Inspiration** - Modern web design trends and glass-morphism effects

## 📊 Project Stats

- **Bundle Size**: Single HTML file (~15KB)
- **Dependencies**: 2 external libraries (CDN)
- **Load Time**: < 1 second on modern connections
- **Languages Supported**: 190+ programming languages
- **Mobile Responsive**: 100% compatible

---

**Made with ❤️ for the markdown community**

*Happy writing!* ✨
