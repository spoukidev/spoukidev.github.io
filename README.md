# spoukidev.github.io

Personal portfolio site of Hamoudi Ahmed Iyad (Spouki): automation engineer (n8n and AI workflows) and AI red teamer.

**Live site:** https://spoukidev.github.io/

## What's on the page

- **Services:** n8n and AI workflow automation, AI agent and chatbot security testing, web and API security checks, security operations automation and network/server hardening
- **Work:** selected projects with video demos
- **Wins:** awards and certifications, including the Gray Swan Arena prize
- **About** and **Contact**
- Light/dark mode toggle

## Project structure

```text
index.html   The whole site: markup, styles and a small script
media/       Project videos, poster frames and review screenshots
```

There is no build step and no dependencies apart from Google Fonts.

## Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

GitHub Pages publishes the `main` branch root automatically. Push to `main` and the live site updates within a minute or two.
