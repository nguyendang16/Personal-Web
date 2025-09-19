# 📸 Profile Image Setup Guide

## How to Add Your Profile Picture

Your website is ready to display your profile picture! Here's how to add it:

### 🔗 Method 1: Using Image URL (Recommended)

1. **Upload your image** to an image hosting service:
   - [GitHub](https://github.com) (create a public repository and upload image)
   - [Imgur](https://imgur.com)
   - [Cloudinary](https://cloudinary.com)
   - [ImageBB](https://imgbb.com)

2. **Get the direct image URL** (should end with .jpg, .png, .gif, etc.)

3. **Update the website**:
   - Open `index.html`
   - Find line with: `src="your-image-url-here.jpg"`
   - Replace `your-image-url-here.jpg` with your actual image URL

**Example:**
```html
<!-- Before -->
<img src="your-image-url-here.jpg" alt="Dang Khoi Nguyen Profile" class="profile-image">

<!-- After -->
<img src="https://i.imgur.com/yourimage.jpg" alt="Dang Khoi Nguyen Profile" class="profile-image">
```

### 📁 Method 2: Using Local File

1. **Add your image** to the website folder:
   - Place your image file (e.g., `profile.jpg`) in the same folder as `index.html`

2. **Update the website**:
   - Open `index.html`
   - Replace `your-image-url-here.jpg` with your filename (e.g., `profile.jpg`)

**Example:**
```html
<img src="profile.jpg" alt="Dang Khoi Nguyen Profile" class="profile-image">
```

### 📐 Image Requirements

- **Format**: JPG, PNG, or WebP
- **Size**: Minimum 250x250 pixels (square aspect ratio recommended)
- **File size**: Keep under 500KB for fast loading
- **Quality**: High resolution for crisp display

### 🎨 Image will automatically:
- ✅ Resize to 250x250 pixels
- ✅ Crop to circular shape
- ✅ Add blue border
- ✅ Apply hover effects
- ✅ Fallback to icon if image fails to load

### 💡 Pro Tips:

1. **Use a square image** (1:1 aspect ratio) for best results
2. **Ensure your face is centered** in the image
3. **Use good lighting** and high contrast
4. **Professional headshot** works best for career websites

### 🔧 Troubleshooting:

**Image not showing?**
- Check the URL is correct and public
- Ensure the URL ends with image extension (.jpg, .png, etc.)
- Try opening the image URL directly in your browser

**Image looks blurry?**
- Use higher resolution image (at least 500x500 pixels)
- Compress using tools like [TinyPNG](https://tinypng.com)

**Image too large/small?**
- The CSS will automatically resize it, but start with square images for best results

---

**Need help?** The website will show a placeholder icon if the image fails to load, so your site will always look professional!
