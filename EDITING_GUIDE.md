# 📝 GitHub Direct Editing Guide

## Quick Start: Edit Files on GitHub

### Step 1: Navigate to File
1. Go to https://github.com/takumaccho/marina-blog-english
2. Click on the file you want to edit (e.g., `index.html`, `styles.css`)

### Step 2: Enter Edit Mode
1. Click the **pencil icon (✏️)** in the top-right corner of the file view
2. The file will open in GitHub's editor

### Step 3: Make Changes
1. Edit the content directly in the browser
2. Use GitHub's syntax highlighting for easier editing

### Step 4: Save Changes
1. Scroll down to "Commit changes" section
2. Add a descriptive commit message (e.g., "Update homepage title")
3. Choose "Commit directly to the main branch"
4. Click **"Commit changes"**

### Step 5: View Changes
- Changes will be live on https://takumaccho.github.io/marina-blog-english/ in 2-5 minutes

---

## 🎯 Common Editing Tasks

### ✏️ Change Page Title
**File:** `index.html`
**Line:** Around line 6
```html
<title>Risa's Growth Journey</title>
```

### 🎨 Change Colors
**File:** `styles.css`
**Lines:** Search for color values like `#FF6B5A`, `#FF9F8A`
```css
.hero h2 {
    color: #FF6B5A; /* Change this color */
}
```

### 📝 Add New Blog Post
**File:** `index.html`
**Section:** Copy existing `<article class="post-card">` block and modify content

### 🖼️ Change Images
**File:** `index.html`
**Find:** `https://via.placeholder.com/` URLs
**Replace:** With your own image URLs

---

## 📱 File Overview

### `index.html` - Main Content
- Page structure and content
- Blog posts and text
- Navigation menu
- Meta information

### `styles.css` - Visual Design  
- Colors and fonts
- Layout and spacing
- Responsive design
- Animations and effects

### `script.js` - Functionality
- Mobile menu behavior
- Interactive animations
- Image loading effects

---

## ⚠️ Important Tips

1. **Always add commit messages** describing your changes
2. **Test on mobile** - site is responsive
3. **Preview changes** by visiting the live site after committing
4. **Keep backups** - GitHub maintains version history
5. **Small changes first** - test one thing at a time

## 🚨 If Something Breaks

1. Go to repository main page
2. Click **"commits"** to see history
3. Find your last working commit
4. Click **"Revert"** to undo problematic changes

---

## 📞 Need Help?

- **GitHub Docs**: https://docs.github.com/en/repositories/working-with-files  
- **HTML Reference**: https://developer.mozilla.org/en-US/docs/Web/HTML
- **CSS Reference**: https://developer.mozilla.org/en-US/docs/Web/CSS