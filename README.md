# Personal Portfolio Website

## 1. Project Overview

This project is a simple, responsive personal portfolio website. It introduces the owner, shows sample projects, and provides a contact section. The website is made with static HTML and CSS and is suitable for learning the basics of web hosting and deployment.

## 2. Technologies Used

- **HTML5** — defines the content and structure of the website.
- **CSS3** — controls layout, colours, spacing, and responsive styling.
- **Git and GitHub** — store and manage the project files.
- **GitHub Pages** — hosts the static website.

## 3. Selected Hosting Platform

**Platform:** GitHub Pages

GitHub Pages publishes static website files directly from a GitHub repository. This project does not require a backend server, database, build tool, or paid hosting plan.

## 4. Prerequisites

- A GitHub account.
- A web browser.
- The project files: `index.html` and `style.css`.
- (Optional) A code editor such as Visual Studio Code for editing files.

No software installation or package manager is required to view the site locally.

## 5. Setup and Configuration

1. Download or clone this repository.
2. Keep `index.html`, `style.css`, and `README.md` in the same root folder.
3. Open `index.html` in a browser to preview the site locally.
4. Personalise the page by replacing `Your Name`, the sample project descriptions, and `your-email@example.com` in `index.html`.
5. If needed, adjust colours, spacing, and responsive styling in `style.css`.
6. Save your changes. Make sure the HTML file is named exactly `index.html` because GitHub Pages uses it as the default home page.

There are no environment variables, API keys, or secrets required.

## 6. Step-by-Step Deployment on GitHub Pages

### A. Create a GitHub repository

1. Sign in to [GitHub](https://github.com/).
2. Select **New repository**.
3. Enter a repository name, for example `my-portfolio`.
4. Choose **Public** if you want to use GitHub Pages with the free plan.
5. Create the repository. If you already have the project files locally, you can leave the option to add a README unchecked.

### B. Upload the project files

1. Open the new repository.
2. Select **Add file → Upload files**.
3. Upload `index.html`, `style.css`, and `README.md` from this project folder.
4. Select **Commit changes** to save the files to the `main` branch.

Alternatively, use Git to push the files from your computer if you are familiar with Git commands.

### C. Enable GitHub Pages

1. In the repository, open **Settings**.
2. In the left sidebar, select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch** as the source.
4. Select the `main` branch and the `/(root)` folder.
5. Click **Save**.
6. Wait for the deployment to finish. You can check the repository's **Actions** tab for the Pages deployment workflow.

### D. Open and verify the website

For a repository named `my-portfolio`, the expected URL format is:

`https://YOUR-GITHUB-USERNAME.github.io/my-portfolio/`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username. The URL will work after the Pages deployment succeeds. Open it in a browser and check that the page and styling load correctly.

## 7. Updating the Website

1. Edit `index.html` or `style.css`.
2. Upload the updated files or commit and push the changes to the `main` branch.
3. Wait for GitHub Pages to redeploy.
4. Refresh the live URL to verify the update.

## 8. Troubleshooting

- **404 error:** Confirm that GitHub Pages is enabled and that `index.html` is in the selected publishing folder.
- **Styles are missing:** Confirm that `style.css` is in the same folder as `index.html` and that the file name matches the link in the HTML.
- **Changes are not visible:** Check the deployment status in the Actions tab, then refresh the page or try a private browser window.
- **URL does not open:** Confirm the GitHub username, repository name, and trailing path in the URL.

## 9. Live Website URL

**Status:** Not deployed yet.

After deployment, replace this line with the verified live URL:

`https://YOUR-GITHUB-USERNAME.github.io/my-portfolio/`

Do not report the site as live until you have opened the URL and confirmed that it works.

## 10. License

This project is provided for educational use. You may adapt it for your own learning portfolio.
