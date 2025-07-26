# 🧪 BackstopJS Visual Automation

This is a sample visual regression testing project using **BackstopJS**.

## Features
- Visual testing for UI snapshots
- Detects pixel-level changes between versions
- Uses Puppeteer under the hood

## Getting Started

1. Install BackstopJS globally:
   ```bash
   npm install -g backstopjs
   ```

2. Start a local server (e.g., `live-server` or `http-server`) to serve `index.html`:
   ```bash
   npx live-server
   ```

3. Run reference test:
   ```bash
   backstop reference
   ```

4. Run test to compare:
   ```bash
   backstop test
   ```

## Folder Structure
- `index.html`: Sample test page
- `backstop.json`: Configuration file
