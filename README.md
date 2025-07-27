# �� Real-time Mood Detector

A professional web application that detects facial expressions and classifies emotions in real-time using computer vision and machine learning.

## 🎯 Live Demo

**[Try it now!](https://your-username.github.io/mood-detector)**

## ✨ Features

- �� **Real-time Camera Detection**: Uses your device's camera for live facial expression analysis
- 😊 **7 Emotion Types**: Detects Happy, Sad, Angry, Surprised, Fearful, Disgusted, and Neutral expressions
- 📊 **Confidence Scoring**: Shows confidence percentage for each detected emotion
- 🎯 **Visual Feedback**: Highlights detected faces with animated bounding boxes and landmarks
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices
- ⚡ **High Performance**: Optimized for smooth real-time detection with FPS counter
- �� **Privacy First**: All processing happens locally in your browser

## 🚀 Quick Start

### Option 1: Live Demo
Visit **[https://your-username.github.io/mood-detector](https://your-username.github.io/mood-detector)**

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/your-username/mood-detector.git
cd mood-detector

# Open in browser
open index.html
```

## 🎮 How to Use

1. **Allow Camera Access**: When prompted, allow the application to access your camera
2. **Wait for Models**: The app will load face detection models (10-30 seconds)
3. **Start Detection**: Click "Start Detection" to begin real-time analysis
4. **Try Expressions**: 
   - **Smile** → Should show "Happy" with high percentage
   - **Frown** → Should show "Sad" with high percentage
   - **Open mouth** → Should show "Surprised"
   - **Angry face** → Should show "Angry"

## 🔧 Technologies Used

- **face-api.js**: Advanced facial detection and expression recognition
- **TensorFlow.js**: Machine learning framework for expression classification
- **HTML5 Canvas**: Real-time video processing
- **CSS3**: Modern, responsive UI with animations
- **Vanilla JavaScript**: Clean, efficient code without heavy frameworks

## 📊 Supported Expressions

1. **Happy** 😊 - Smiling, raised cheeks, crinkled eyes
2. **Sad** �� - Downturned mouth, drooping eyes
3. **Angry** 😠 - Furrowed brow, tight jaw, narrowed eyes
4. **Surprised** �� - Raised eyebrows, wide eyes, open mouth
5. **Fearful** 😨 - Wide eyes, raised eyebrows, tense mouth
6. **Disgusted** 🤢 - Wrinkled nose, raised upper lip
7. **Neutral** �� - Relaxed, natural expression

## 🌐 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+

## �� Privacy & Security

- **Local Processing**: All facial analysis happens in your browser
- **No Data Upload**: No images or data are sent to external servers
- **Camera Access**: Only active when you explicitly start the camera
- **Secure**: Uses HTTPS for camera access and modern web APIs

## 🚀 Deployment

This project is designed to be deployed on GitHub Pages:

1. **Fork this repository**
2. **Enable GitHub Pages** in repository settings
3. **Set source to main branch**
4. **Your app will be live at**: `https://your-username.github.io/mood-detector`

## 📁 Project Structure

```
mood-detector/
├── index.html          # Main application file
├── README.md           # This documentation
└── .gitignore          # Git ignore file
```

## 🐛 Troubleshooting

### Common Issues

1. **Camera not working**
   - Check browser permissions
   - Ensure HTTPS connection (required for camera access)
   - Try refreshing the page

2. **Poor detection accuracy**
   - Improve lighting conditions
   - Position face closer to camera
   - Remove obstructions (glasses, hats)

3. **Models not loading**
   - Check internet connection
   - Refresh the page
   - Clear browser cache

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- [face-api.js](https://github.com/justadudewhohacks/face-api.js) for facial detection and expression recognition
- [TensorFlow.js](https://www.tensorflow.org/js) for machine learning capabilities

---

**Made with ❤️ for real-time emotion detection**
EOF
```

### **3. Create .gitignore file**

```bash
# Dependencies
node_modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Build outputs
dist/
build/

# Environment variables
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# IDE files
.vscode/
.idea/
*.swp
*.swo

# OS generated files
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Logs
logs
*.log

# Runtime data
pids
*.pid
*.seed
*.pid.lock

# Coverage directory used by tools like istanbul
coverage/

# Temporary folders
tmp/
temp/
```

### **4. Create LICENSE file**

```bash
# Create MIT License
cat > LICENSE << 'EOF'
MIT License

Copyright (c) 2024 Mood Detector

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
EOF
```

### **5. Update the title in index.html**

Let me check the current title and update it:
