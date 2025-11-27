# Quarterly Earnings Presentation - GitHub Pages Deployment Guide

## Quick Start for GitHub Pages

Follow these steps to deploy your presentation on GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click **+** (top right) → **New repository**
3. Name it: `quarterly-earnings-presentation`
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files

You have two options:

#### Option A: Using Git Command Line
```bash
# Clone the repository to your local machine
git clone https://github.com/YOUR_USERNAME/quarterly-earnings-presentation.git

# Navigate to the folder
cd quarterly-earnings-presentation

# Copy the index.html and README.md files to this folder

# Stage all files
git add .

# Commit the files
git commit -m "Initial commit: Add quarterly earnings presentation"

# Push to GitHub
git push origin main
```

#### Option B: Drag & Drop Upload
1. Go to your repository on GitHub
2. Click **Add file** → **Upload files**
3. Drag and drop `index.html` and `README.md`
4. Commit the changes

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Select **Pages** from the left sidebar
4. Under "Build and deployment":
   - **Source**: Select **Deploy from a branch**
   - **Branch**: Select **main** (or **master**)
   - **Folder**: Select **/ (root)**
5. Click **Save**

GitHub will show you the live URL after a few seconds.

### Step 4: Access Your Presentation

Your presentation will be available at:
```
https://YOUR_USERNAME.github.io/quarterly-earnings-presentation/
```

For example, if your GitHub username is `john-doe`:
```
https://john-doe.github.io/quarterly-earnings-presentation/
```

---

## Presentation URL Format

**GitHub Pages URL Structure:**
```
https://[USERNAME].github.io/[REPOSITORY]/
```

Replace:
- `[USERNAME]` with your GitHub username
- `[REPOSITORY]` with `quarterly-earnings-presentation`

---

## Updating Your Presentation

To make changes to your presentation:

1. Edit `index.html` locally
2. Commit and push changes:
   ```bash
   git add index.html
   git commit -m "Update slide content"
   git push origin main
   ```
3. Wait 30 seconds - 2 minutes for GitHub Pages to rebuild
4. Refresh your browser to see changes

---

## Features Available in Your Presentation

✅ **Email Contact** - 22f3002140@ds.study.iitm.ac.in (on title slide)
✅ **Markdown Slides** - Revenue performance section with data tables
✅ **Animated Fragments** - Executive summary with bullet point animations
✅ **Code Samples** - Python, SQL, and JavaScript with syntax highlighting
✅ **Mathematical Equations** - Financial formulas (ROE, EPS, FCF) using MathJax
✅ **Speaker Notes** - Guidance on every slide (press 'S' to view)

---

## Sharing Your Presentation

### Share the URL
Simply share the GitHub Pages URL with stakeholders:
```
https://YOUR_USERNAME.github.io/quarterly-earnings-presentation/
```

### Download for Offline Use
1. Click **Code** → **Download ZIP**
2. Extract and open `index.html` in a browser

### Present from Browser
- Full screen: Press **F**
- Speaker notes: Press **S**
- Slide overview: Press **ESC**
- Navigate: Arrow keys or mouse clicks

---

## Troubleshooting

### Presentation not loading?
- Wait 2-5 minutes after pushing to GitHub (Pages deployment)
- Check that `index.html` is in the root folder
- Verify the repository is set to Public
- Check GitHub Pages settings are enabled

### Styling not showing?
- Clear browser cache (Ctrl+Shift+Delete)
- Check that CDN links are accessible (internet connection required)
- Try a different browser

### Speaker notes not opening?
- Ensure you're viewing in a modern browser
- Try pressing **S** while on a slide
- Check browser console for errors (F12)

---

## Customization Tips

### Change Theme Colors
In `index.html`, find the `<style>` section and modify:
```css
.reveal h1, .reveal h2, .reveal h3 {
    color: #4CAF50;  /* Change to your color */
}

.financial-metric {
    background: rgba(76, 175, 80, 0.15);  /* Adjust transparency */
}
```

### Change Theme Style
Replace this line:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.5.0/theme/black.min.css">
```

Available themes: `black`, `white`, `league`, `sky`, `beige`, `simple`, `serif`, `blood`, `night`, `moon`, `solarized`

### Add More Slides
Copy and modify the existing slide structure in `index.html`

### Update Contact Email
Find and replace `22f3002140@ds.study.iitm.ac.in` with your email throughout the file

---

## Resources

- **RevealJS Documentation:** https://revealjs.com/
- **GitHub Pages Help:** https://docs.github.com/en/pages
- **MathJax Documentation:** https://www.mathjax.org/
- **Highlight.js Languages:** https://highlightjs.org/

---

## Support

For help with your presentation:
1. Check the troubleshooting section above
2. Review RevealJS documentation at revealjs.com
3. Contact GitHub support for Pages issues
4. Reach out at: 22f3002140@ds.study.iitm.ac.in

---

**Created:** November 27, 2024
