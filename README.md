# Local JSON Configuration

A lightweight, browser-based configuration generator for OpenAI-compatible models. Choose a model and its supported options, then copy a ready-to-use JSON configuration block for your coding extension.

## Features

- Browse and search a curated list of model configurations.
- Set token limits and, where supported, temperature and reasoning options.
- Preview generated JSON as you change settings.
- Copy a configuration block to your clipboard.
- Responsive dark interface.

## Technologies

<p align="left">
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS (CDN)" />
  </a>
  <a href="https://lucide.dev/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Lucide_Icons-F56565?style=for-the-badge&logo=lucide&logoColor=white" alt="Lucide Icons (CDN)" />
  </a>
</p>

The project is implemented in a single `index.html` file. It uses vanilla JavaScript for the interactive model cards and JSON generation, Tailwind CSS via CDN for utility styling, and Lucide icons via CDN. Custom styles are included in the HTML file.

## Run locally

No build step or package installation is required. Clone or download the repository and open `index.html` in a modern browser.

## Usage

1. Search for a model in the sidebar.
2. Adjust the available token, temperature, or reasoning settings.
3. Review the generated JSON configuration.
4. Select **Copy** to copy it to your clipboard.

## Notes

The generated configuration currently includes a placeholder API key (`dummy-key`) and the API base URL configured in `index.html`. Replace these with values appropriate for your own setup before using the configuration.
