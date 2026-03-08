# Responsive Multi-Theme CV Editor

A feature-rich, browser-based Curriculum Vitae (CV) / Resume editor built with vanilla HTML, CSS, and JavaScript. It features real-time editing, live Firebase synchronization, image cropping, and the ability to instantly generate high-quality a4-sized PDF downloads using html2canvas and jsPDF.

## Features

- **5 Unique Themes**:
  - **Classic**: The original clean, straightforward design.
  - **Modern**: A professional blue/gray palette with ATS-friendly aesthetics.
  - **Premium**: A stylish dark sidebar with indigo/cyan accents.
  - **Glass Modern**: A futuristic glassmorphism design with a vibrant gradient background.
  - **Optometric Clean**: A medical-inspired dashboard aesthetic with soft cyan accents.
- **Download All Themes**: Instantly iterate through the 5 themes and download 5 uniquely styled PDFs in one click.
- **Responsive Design**: The editor adapts seamlessly to mobile devices, stacking columns vertically, but intelligently isolates the DOM during "Download as PDF" so the generated PDFs maintain their perfect A4 computer-view proportions.
- **Firebase Sync**: Connects to Firebase Realtime DB. Typing in any field automatically saves your changes.
- **Profile Photo Uploading**: Includes an integrated Cropper.js modal to ensure your profile picture is perfectly squared before insertion.

## Tech Stack
- HTML5 / CSS3 / Vanilla JavaScript
- Font Awesome (Icons)
- Google Fonts (Inter, Poppins, Montserrat, Playfair Display)
- html2canvas & jsPDF (Client-side PDF generation)
- Cropper.js (Image manipulation)
- Firebase Realtime Database (Data persistence)

## Setup & Usage

1. Open `index.html` in your browser (or run a local development server `npx serve .`).
2. Click any text field (Name, Profile, Skills, etc.) and start typing to update.
3. Click the Image placeholder to upload and crop a new profile picture.
4. Use the **Theme** button to cycle through the 5 available designs.
5. Click **Download as PDF** to generate an A4-sized PDF of your current active theme.
6. Click **Download All Themes** to save a batch of PDFs—one for each theme.

Enjoy building your responsive resumé!
