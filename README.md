# Interactive Branching Video Player Web App

A modern, dark-mode, choice-driven video experience built with vanilla JavaScript, Tailwind CSS, and Lucide Icons. Viewers make decisions that branch the video timeline in real time, encounter shoppable product hotspots, and complete in-video knowledge checks — all wrapped in a fully responsive, single-file web app.

## Features

- **Branching Logic** — Native `timeupdate` event listener pauses playback at key timestamps and routes viewers down different video paths based on their choices.
- **Shoppable Hotspots** — Pulsing, native-feeling product overlay cards let viewers add items to a persistent cart directly from the video.
- **In-Video Quizzes** — Multiple-choice knowledge checks with instant visual feedback (correct/incorrect states) before playback resumes.
- **Mobile Responsive Layout** — Theater-mode video container, sticky nav, and overlay cards all adapt cleanly across mobile, tablet, and desktop breakpoints.

## Tech Stack

- Vanilla HTML5 & JavaScript (no build step, no frameworks)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Lucide Icons](https://lucide.dev/) via CDN
- Single self-contained `index.html` file

## Getting Started (Local Preview)

1. Clone this repository:
```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
```
2. Open `index.html` directly in any modern browser — no server or build tools required.

## Deployment (Netlify)

This project deploys as a static site with zero configuration.

1. Push this repository to GitHub (ensure `index.html` sits at the project root).
2. Log in to [Netlify](https://app.netlify.com/) and click **Add new site → Import an existing project**.
3. Choose **GitHub** as your Git provider and authorize Netlify to access your repositories.
4. Select this repository from the list.
5. Configure the build settings:
   - **Build command:** *(leave blank — no build step needed)*
   - **Publish directory:** `/` (root)
6. Click **Deploy site**. Netlify will assign a live URL (e.g., `your-site-name.netlify.app`) within seconds.
7. (Optional) Go to **Site settings → Domain management** to attach a custom domain.

Every future push to your connected branch (typically `main`) will automatically trigger a new Netlify deploy.

## Project Structure
