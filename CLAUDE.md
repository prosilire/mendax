# CLAUDE.md - Guidelines for Mendax News

## Commands
- **View site**: Open `index.html` in a browser
- **Validate HTML**: Run `npx html-validator-cli --file=index.html`
- **Validate CSS**: Run `npx stylelint "css/*.css"`

## Code Style Guidelines

### HTML
- Use HTML5 doctype and semantic elements
- Indent with 4 spaces
- Use lowercase for element names and attributes
- Include alt text for all images
- Use valid href/src paths with proper slashes

### CSS
- Prefer external CSS in the css/ directory
- Follow BEM naming convention
- Use hex codes for colors (#333 not gray)
- Order properties alphabetically

### Images
- Store in /images directory
- Use descriptive filenames with dashes
- Optimize for web (compress JPG/PNG)

### Project Structure
- Maintain flat directory hierarchy
- Keep HTML files in root
- Place stylesheets in /css
- Place images in /images

### Best Practices
- Ensure responsive design (use viewport meta)
- Include appropriate meta tags for SEO/social sharing
- Test across multiple browsers