# Image Sources for The Modern Frame Gallery

## Free Art Image Resources

### 1. Unsplash Art Collection
- **URL**: https://unsplash.com/s/photos/art
- **Usage**: Free for commercial use
- **Examples**: 
  - Abstract paintings: https://unsplash.com/s/photos/abstract-painting
  - Sculptures: https://unsplash.com/s/photos/sculpture
  - Gallery spaces: https://unsplash.com/s/photos/art-gallery

### 2. Pexels Art Collection
- **URL**: https://www.pexels.com/search/art/
- **Usage**: Free for commercial use
- **Examples**:
  - Modern art: https://www.pexels.com/search/modern%20art/
  - Paintings: https://www.pexels.com/search/painting/

### 3. Pixabay Art Collection
- **URL**: https://pixabay.com/images/search/art/
- **Usage**: Free for commercial use
- **Examples**:
  - Contemporary art: https://pixabay.com/images/search/contemporary%20art/
  - Oil paintings: https://pixabay.com/images/search/oil%20painting/

### 4. Art Museums with Open Access
- **Metropolitan Museum of Art**: https://www.metmuseum.org/art/collection
- **National Gallery of Art**: https://www.nga.gov/collection/
- **Art Institute of Chicago**: https://www.artic.edu/collection

## How to Replace Placeholder Images

1. **Download images** from the sources above
2. **Save them** in the `images/` folder with descriptive names:
   - `abstract-composition.jpg`
   - `urban-landscape.jpg`
   - `sculpture-metamorphosis.jpg`
   - etc.

3. **Update HTML files** to use local images instead of Picsum URLs:
   ```html
   <!-- Change from: -->
   <img src="https://picsum.photos/400/300?random=1" alt="Abstract Composition">
   
   <!-- To: -->
   <img src="images/abstract-composition.jpg" alt="Abstract Composition in Blue and Gold">
   ```

## Video Options

### Option 1: Create a Real Gallery Tour Video
- Record a video tour of an actual gallery space
- Use your phone or camera to film artwork and gallery spaces
- Edit with free tools like iMovie, DaVinci Resolve, or OpenShot

### Option 2: Use Stock Video
- **Pexels Videos**: https://www.pexels.com/videos/
- **Pixabay Videos**: https://pixabay.com/videos/
- Search for "art gallery", "museum", "artwork"

### Option 3: Use YouTube Embed
Replace the video element with an iframe:
```html
<iframe 
    width="100%" 
    height="400" 
    src="https://www.youtube.com/embed/VIDEO_ID" 
    frameborder="0" 
    allowfullscreen>
</iframe>
```

## Recommended Image Sizes
- **Gallery thumbnails**: 400x300px
- **Hero images**: 1200x600px
- **About page images**: 400x300px
- **Contact page images**: 400x300px

## File Formats
- **Photos**: Use .jpg for photos, .png for graphics with transparency
- **Video**: Use .mp4 for web compatibility
- **Optimize**: Compress images to reduce file size (aim for under 500KB per image) 