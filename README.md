# Complete HTML Downloader Chrome Extension

## Description

The Complete HTML Downloader is a Chrome extension that allows users to download an entire web page as a single HTML file, including all inline styles, images, and other resources. This extension is perfect for web developers, designers, or anyone who needs to save a complete webpage for offline viewing or archival purposes.

## Features

- Downloads the entire webpage as a single HTML file
- Inlines all external CSS files
- Converts images to base64-encoded data URIs
- Resolves relative URLs to absolute URLs in CSS
- Simple one-click download process

## Installation

1. Clone this repository or download it as a ZIP file and extract it.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" in the top right corner.
4. Click "Load unpacked" and select the directory containing the extension files.

## Usage

1. Navigate to the webpage you want to download.
2. Click on the Complete HTML Downloader extension icon in your Chrome toolbar.
3. In the popup that appears, click the "Download" button.
4. The webpage will be processed, and a file named `index.html` will be downloaded to your default download location.
5. Open the downloaded HTML file in a web browser to view the complete webpage offline.

## File Structure

- `manifest.json`: Extension configuration file
- `popup.html`: HTML structure for the extension popup
- `popup.js`: JavaScript for handling user interaction in the popup
- `content.js`: Core logic for processing and downloading the webpage
- `icons/`: Directory containing extension icons

## Permissions

This extension requires the following permissions:

- `activeTab`: To access and modify the content of the current tab
- `scripting`: To inject and execute scripts in web pages
- `<all_urls>`: To fetch resources from any URL (necessary for inlining external resources)

## Contributing

Contributions to improve the Complete HTML Downloader are welcome. Please feel free to submit issues or pull requests.

## License

[MIT License](LICENSE)

## Disclaimer

This extension is for personal use and educational purposes only. Always respect copyright laws and website terms of service when using this extension.