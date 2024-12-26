# Commands Used

This file tracks all commands used in setting up and developing the Angular project.

```bash
# Install Angular CLI globally
npm install -g @angular/cli

# Create new Angular project with routing and SCSS
ng new my-portfolio --routing true --style scss

# Generate landing page component
cd my-portfolio && ng generate component landing-page

# Start development server
cd my-portfolio && ng serve

# Install Angular CLI
cd my-portfolio && npm install angular-cli-ghpages --save-dev

# Deploy to GitHub Pages
cd my-portfolio && ng build --configuration production --base-href "/"

# Push to GitHub Pages
cd my-portfolio && npx angular-cli-ghpages --dir=dist/my-portfolio/browser --name="Palak Sharma" --email="palak642@gmail.com"

# Combined Command
npm run deploy
