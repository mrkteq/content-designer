# Content Designer Portfolio

Static portfolio website demonstrating content design process, rationale, and execution across three case studies.

For more about my frontend development experience and projects, visit my [portfolio](https://github.com/mrkteq/marktucker-portfolio).

## Technical Stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (scroll behavior, back-to-top)
- No frameworks, no build process

## Features

- Mobile-first responsive design
- Dark mode support (system preference)
- Reduced motion support (accessibility)
- Print-optimized styles
- Custom scrollbars (webkit)
- Smooth scroll navigation
- Expandable artifact sections

## Typography

- **Headings**: Crimson Pro (serif)
- **Body**: Inter (sans-serif)
- **Code**: Courier New (monospace)

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari 14+, Chrome Android)

## File Structure

```
index.html          # Single-file portfolio (self-contained)
README.md           # This file
```

## Performance

- First Contentful Paint: <1s
- Total page size: ~50KB
- No external dependencies (fonts loaded from Google Fonts)
- CSS animations: GPU-accelerated
- Zero JavaScript required for core functionality

## Accessibility

- Semantic HTML5 elements
- ARIA labels on interactive elements
- Keyboard navigation support
- Focus visible states
- Color contrast WCAG AA compliant
- Respects prefers-reduced-motion
- Respects prefers-color-scheme

## Customization

### Colors

Modify CSS custom properties in `:root`:

```css
--black: #0a0a0a;
--white: #fafafa;
--accent: #d62828;
```

### Typography

Replace Google Fonts link and update variables:

```css
--serif: 'Crimson Pro', serif;
--sans: 'Inter', sans-serif;
```

### Content

Edit HTML directly. Case study structure:

```html
<article>
  <h3>Title</h3>
  <h4>Context</h4>
  <p>...</p>
  <h4>Discovery</h4>
  <p>...</p>
  <h4>Content Decisions</h4>
  <p>...</p>
  <details>
    <summary>View Artifact</summary>
    <div class="artifact-content">
      <pre>...</pre>
    </div>
  </details>
  <h4>Outcome</h4>
  <p>...</p>
</article>
```

