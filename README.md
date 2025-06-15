# LocalLingo

LocalLingo is a completely offline private translation Chrome extension. It performs translations using Chrome's built-in Translator and Language Detector APIs without any network communication.

## Features

- 🔒 **Completely Offline** - No network communication, privacy protection guaranteed
- 🚀 **Instant Translation** - Lightning-fast translation with Chrome's built-in APIs
- 📝 **Text Selection Translation** - Simply select text on any webpage to translate
- ⚙️ **Site-specific Settings** - Disable functionality on specific websites
- 🎯 **Replace & Copy** - Replace selected text or copy translation results

## How to Use

1. **Select Text**: Highlight the text you want to translate on any webpage
2. **Click Translate Button**: Click on the translation button that appears
3. **Use Results**: 
   - **Replace**: Replace the selected text with the translation
   - **Copy**: Copy the translation result to clipboard
   - **Disable on This Site**: Turn off translation for the current website

## Installation

### Building from Source

1. Install dependencies:
```bash
pnpm install
```

2. Start development server:
```bash
pnpm run dev
```

3. Build for production:
```bash
pnpm run build
```

4. Load the extension in Chrome:
   - Open `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the `dist` folder

## Technical Specifications

- **Framework**: React + TypeScript
- **Build Tool**: Vite + CRXJS
- **Translation Engine**: Chrome's built-in Translator and Language Detector APIs
- **Browser Support**: Chrome 120+

## Project Structure

- `src/popup/` - Extension popup UI
- `src/content/` - Content scripts (main translation functionality)
- `manifest.config.ts` - Chrome extension configuration

## Privacy

LocalLingo operates completely offline and guarantees:
- No network communication
- No external data transmission
- All translation processing performed locally
- Complete user privacy protection

## License

MIT License
