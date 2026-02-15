# Audio Converter Web App

A powerful browser-based audio converter powered by FFmpeg.wasm that runs entirely on the client side. Convert various audio formats to WAV without any server uploads or installations.

## 🚀 Features

- **100% Client-side**: All conversions happen locally in your browser - no server uploads required
- **Multiple Format Support**: Convert from MP3, AAC, M4A, OGG, FLAC, and more to WAV
- **Drag & Drop Interface**: Easy file selection with drag and drop support
- **Real-time Progress**: Visual feedback during conversion process
- **Mobile Friendly**: Responsive design that works on smartphones and tablets
- **PWA Ready**: Install as a progressive web app for offline access
- **Privacy Focused**: Your files never leave your device

## 🛠️ How It Works

This application uses FFmpeg.wasm, a WebAssembly version of FFmpeg, to perform audio conversion directly in your browser. When you select a file, FFmpeg loads in the background and processes the audio using your device's resources.

## 📋 Supported Input Formats

- MP3
- AAC
- M4A
- WAV
- OGG
- FLAC
- And most other common audio formats

## 🎯 Output Format

All files are converted to:
- **Format**: WAV (PCM 16-bit)
- **Sample Rate**: 44.1 kHz
- **Channels**: Stereo (2 channels)

## 🚦 Getting Started

### Online Version
Visit the live application at: [https://souzamonteiro.github.io/audioconverterwebapp](https://souzamonteiro.github.io/audioconverterwebapp)

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/souzamonteiro/audioconverterwebapp.git
cd audioconverterwebapp
```

2. Serve the files using a local web server. For example, using Python:
```bash
python -m http.server 8000
```

3. Open your browser and navigate to `http://localhost:8000`

### Prerequisites
- A modern web browser with WebAssembly support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Sufficient device memory for processing audio files

## 📱 PWA Installation

The app can be installed as a Progressive Web App:
- **Android**: Use "Add to Home screen" from Chrome
- **iOS**: Use "Add to Home Screen" from Safari
- **Desktop**: Click the install icon in the address bar

## 🔧 Technical Details

The application uses:
- **FFmpeg.wasm** ([https://ffmpegwasm.netlify.app/](https://ffmpegwasm.netlify.app/)) - FFmpeg compiled to WebAssembly
- **Service Workers** - For offline functionality
- **File API** - For handling local file operations
- **Web Workers** - For background processing

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

```
Copyright 2024 Audio Converter Web App Contributors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Limitations

- Large files may take significant time and memory to process
- Conversion speed depends on your device's processing power
- Some rare audio formats may not be supported

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on [GitHub](https://github.com/souzamonteiro/audioconverterwebapp/issues)
- Check the [FFmpeg.wasm documentation](https://github.com/ffmpegwasm/ffmpeg.wasm)

## 🙏 Acknowledgements

- [FFmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) for making FFmpeg available in the browser
- The FFmpeg project for the amazing multimedia framework
- All contributors and users of this project

## 📊 Project Status

Active development - Bug fixes and improvements are ongoing.

---

**Made with ❤️ for audio conversion**