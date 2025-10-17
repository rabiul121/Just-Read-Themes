
# Just Read — Custom themes for the Just Read extension

This repository contains a collection of custom themes and small UX tweaks for the Just Read browser extension (Chromium-based browsers). It also includes an optional summarizer integration that supports OpenAI / Google Gemini API keys so you can generate short summaries of the current article from within the extension.

Key changes in this update

- Added support for using Gemini/OpenAI APIs to summarize the selected article text from the extension.

- New themes for English and Bengali (Bangla) in Light, Dark and Image-background variants.

- Minor popup and UI tweaks to reduce distractions while reading.

Note: This repo provides theme CSS and instructions to load the extension locally. The summarizer feature requires that you provide your own API key for Gemini or OpenAI.

## Installation (Local/Unpacked extension)

1. Unzip the provided `just-read.zip` file to a folder on your machine.
2. Open your Chromium-based browser (Chrome, Brave, Microsoft Edge, etc.).
3. Open the Extensions manager:

   - Chrome/Brave: Menu → More tools → Extensions, or go to chrome://extensions/

   - Edge: Menu → Extensions, or go to edge://extensions/
4. Enable "Developer mode" (top-right) and click "Load unpacked".
5. Select the folder you unzipped in step 1. The extension will be added to the browser.

## Setting up the Summarizer (Gemini / OpenAI)

1. Right-click the Just Read extension icon in your browser's extension toolbar and choose "Options".
2. In the options page, paste your API key for Gemini or OpenAI.
3. Select the model you want to use (for example: gpt-4o, gpt-4, or a Gemini model) from the model dropdown.
4. Click Save.
5. Open any article, activate Just Read, and use the Summarizer feature in the extension UI to generate summaries.

Notes about API keys

- Keep your API key private and never commit it to a public repository.

- This extension does not ship with an API key.

## Themes included

- English: light and dark themes, plus image-background variants.
- Bengali (Bangla): light, dark and image-background themes, including styles tuned for common Bengali fonts.
- Fonts are provided under the `Fonts/` folder. Install them on your system if you want to use the shipped fonts.

To install a theme:

1. Open the Just Read Options page (right-click the extension icon → Options).

2. Create a new theme, paste the CSS from any of the files in this repo (or the theme backup folder), and Save.

## Bundled themes (detailed list)

Below is a list of the bundled theme files included in this repository with short descriptions.

Dark

English

- `eng-dark-arial.css` — Dark (Arial)
- `eng-dark-helvatica.css` — Dark (Helvetica)
- `eng-dark-roboto.css` — Dark (Roboto)

Bengali

- `bn-dark-solaimanlipi.css` — ডার্ক (SolaimanLipi)

Light

English

- `eng-bn-light-noto-serif-ben.css` — Light (Noto Serif Bengali)
- `eng-lexend.css` — Light (Lexend)
- `eng-light-georgia.css` — Light (Georgia)
- `eng-light-open-sans.css` — Light (Open Sans)
- `eng-light-poppin.css` — Light (Poppins)
- `english-light-helvatica.css` — Light (Helvetica)

Bengali

- `bn-ekushy-lalsalu.css` — লালসালু (Ekushy)
- `bn-light-bangla.css` — Light (Bangla)
- `bn-light-kalpurush.css` — Light (Kalpurush)
- `bn-light-solaimanlipi.css` — Light (SolaimanLipi)

Background image (bg_image)

Bengali

- `bn-bg_image-kalpurush.css` — Background image (Kalpurush)
- `bn-bg_image-solaimanlipi.css` — Background image (SolaimanLipi)

Print

- `print-en.css` — Print (English)
- `print-bn.css` — Print (Bengali)

## Usage

- Open any article web page.
- Click the Just Read extension icon to enter reading mode.
- Choose your theme from the extension option page or use the saved theme from the list.
- To summarize the article: click the Summarize button (or whichever UI control is present after loading this modification). The extension will call the selected model using the API key you provided and display a short summary.

## Legal / License / Purchase

This modification is provided for educational purposes only. If you enjoy the extension and want the full, packaged experience, please consider purchasing the official version from the original author or the extension marketplace.

If you redistribute any code from this repository, please respect the original author's license and attribution.

## Screenshots

Screenshots are available in the `Screenshots/` folder. Use them to preview themes and options UI.

## Fonts

If you want to use the bundled fonts, install the font files from the `Fonts/` directory on your OS.

## Contact

@Md. Rabiul Islam

- Email: <robiu121@proton.me>
