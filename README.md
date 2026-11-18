# Silent MV 🎬🔇

A lightweight, single-file web app designed to play looping, muted background visuals in fullscreen while your own music or audio plays. Supports both **YouTube links** and **local video files** from your device.

## Features

- **Dual Source Support:** Instantly launch YouTube videos (via standard links, `youtu.be`, Shorts, or video IDs) or drag & drop local video files (`.mp4`, `.webm`, `.mkv`, etc.).
- **Muted Autoplay:** Automatically launches muted so it never conflicts with your music player or audio streams.
- **Auto-Looping:** Videos loop continuously by default.
- **Fullscreen First:** Automatically requests browser fullscreen upon playback, with a clean overlay to exit back or toggle fullscreen anytime (press `F` or `Esc`).
- **Error 153 Guard:** Fully configured with `referrerpolicy` and origin headers for seamless hosting on **GitHub Pages**.

## Quick Start

1. Clone or download this repository.
2. Ensure your main file is named `index.html`.
3. Push to a public GitHub repository and enable **GitHub Pages** under your repository settings (`Settings > Pages > Deploy from a branch > main / root`).
