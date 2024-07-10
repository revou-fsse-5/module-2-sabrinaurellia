# Justin Bieber Vespa

## Introduction

This project is a responsive website dedicated to the collaboration between Justin Bieber and Vespa. The website showcases the unique scooter designed by Bieber and provides information about the collaboration.

## Features

- Custom Font using `@font-face` for navigation
- Text Shadow for enhanced text appearance
- Responsive Background Image for better visual impact
- Responsive Images with `picture` + `source` + `srcset` for optimal loading
- Asymmetrical Grid Layout for a unique design
- Simple Animations for a dynamic user experience

## Deployment

### Netlify Sign Up and Project Deployment

1. **Sign Up on Netlify**
   - Go to [Netlify](https://www.netlify.com/).
   - Click on `Sign up` and create an account using your preferred method (GitHub, GitLab, Bitbucket, or email).

2. **Connect Netlify to GitHub**
   - After signing in, click on `New site from Git` on your Netlify dashboard.
   - Choose `GitHub` as the continuous deployment provider.
   - Authorize Netlify to access your GitHub account and select the repository containing your project.
   - Select the branch you want to deploy (typically `main`).

3. **Configure Build Settings**
   - **Base Directory**: Leave this field empty since you don't have a specific base directory for a simple static site.
   - **Build Command**: Leave this field empty since you're not using a build tool.
   - **Publish Directory**: Set this to `/`, or leave empty if your `index.html` is in the root directory.

4. **Deploy Site**
   - Click `Deploy site`. Netlify will start deploying your site and you can monitor the process in the deploy logs.

### Auto Deployment with GitHub Actions

1. **Choose Module 2 repository**

2. **GitHub Actions Workflow Configuration**

website: https://justinbiebervespa.netlify.app
