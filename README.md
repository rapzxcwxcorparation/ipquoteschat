# IPQuotesChat - Powered By RappTzy

## Overview

IPQuotesChat is a browser‑based tool that creates realistic iPhone message screenshots.  
It offers two generation modes (Brat and Deline APIs) with live preview, HD download, and a sleek glass‑morphism design.

## Features

- **Dual API Tabs** – Switch between Brat (v1) and Deline (v2) generators.
- **Live Preview** – See the screenshot update instantly inside a macOS window mockup.
- **HD Download** – Save the generated image in original resolution.
- **Copy URL / View** – Share the direct API link or open it in a new tab.
- **Animated Background** – iOS‑style moving grid with subtle vignette.
- **Interactive Credits** – 3D rotating cube and scramble‑text footer.
- **Responsive Layout** – Optimised for desktop and mobile devices.
- **Fallback Handling** – If the primary API fails, the tool automatically switches to the secondary API with a friendly notice.

## Usage

1. Fill in the message text, carrier, time, battery percentage, and emoji style.
2. Click **GENERATE** to create the preview.
3. Use the action buttons:
   - **SAVE** – Download the screenshot as a PNG file.
   - **COPY URL** – Copy the direct image URL to the clipboard.
   - **VIEW** – Open the image in a new browser tab.
4. Switch between **V1** and **V2** tabs to use different generation APIs.

A **Guide** button provides a quick overview of the steps.

## Technology Stack

- HTML5, CSS3 (Tailwind CSS, custom glass‑morphism)
- JavaScript (Vanilla, Axios)
- Lucide Icons
- Tenor GIF Embed (for loading animation)

## Deployment

The project is a static web application. It can be deployed on any static hosting service.

**Live Demo**: [rapzxcwxcorparation.github.io/ipquoteschat](https://rapzxcwxcorparation.github.io/ipquoteschat/)

### Deploy Your Own

1. Clone the repository.
2. Open `index.html` in a browser, or upload the files to your preferred static host (Vercel, Netlify, GitHub Pages).

## Configuration

The tool uses two public APIs:

- **V1 (Brat)**: `https://brat.siputzx.my.id/iphone-quoted`
- **V2 (Deline)**: `https://api.deline.web.id/maker/iqc`

No API keys are required. If the Brat endpoint is unavailable, the generator automatically falls back to Deline.

## Credits

- Created by RappTzyy
- Mentorship by Professor Kai Vortex
- Background grid inspired by iOS interface concepts

## License

This project is open source. Feel free to use, modify, and share.

---

_*You Want Version Of index.html no enc? Please Contact Me*_
*For questions or collaboration, reach out via the Telegram link inside the application.*