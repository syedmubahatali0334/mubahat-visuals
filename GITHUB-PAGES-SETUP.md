# GitHub Pages Setup & Client Handover

## 1. Publish from your GitHub account

1. Create a public GitHub repository named `mubahat-visuals`.
2. Upload **all project files and folders**, including `.pages.yml` and `.github`.
3. Keep `main` as the default branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **GitHub Actions**.
6. Open **Actions** and wait for **Deploy Mubahat Visuals to GitHub Pages** to finish successfully.
7. Open **Settings → Pages** and test the live URL.

The included workflow replaces the social-preview URL with the actual GitHub Pages site URL during deployment.

## 2. Transfer the finished website to the client

1. Ask the client for their GitHub username. Never ask for their password.
2. Open **Settings → General → Danger Zone → Transfer**.
3. Enter the client's GitHub username and confirm the repository name.
4. The client accepts the GitHub transfer email.
5. After transfer, the client opens **Settings → Pages** and confirms **GitHub Actions** as the source.
6. Run or wait for the deployment workflow again and use the new client-owned GitHub Pages URL.

GitHub does not redirect the old GitHub Pages URL after repository transfer, so always share the new client-owned URL after handover.

## 3. Portfolio dashboard for the client

1. Client opens `https://app.pagescms.org/` and chooses **Sign in with GitHub**.
2. Client installs/authorizes the Pages CMS GitHub App for the transferred repository.
3. Open **Portfolio Projects**.
4. Add a project title, select its category, upload a thumbnail, paste a YouTube Unlisted/Vimeo/direct video URL, and save.
5. GitHub redeploys the updated website automatically.

The client can also open `YOUR-WEBSITE-URL/admin/` for the portfolio-dashboard shortcut.
