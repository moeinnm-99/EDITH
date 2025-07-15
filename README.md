# 📝 EDITH - Virtual Assistant 🤖

<img src="https://github.com/moeinnm-99/EDITH/blob/main/Edith.png">


<div align="center">
  <h1>EDITH Virtual Assistant</h1>
  <p>Your personal AI assistant inspired by Iron Man's EDITH system</p>
  
  [![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
  [![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
  [![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
</div>

## 🌟 Features

- **Voice-controlled** 🎙️ - Natural voice interaction
- **Multi-functional** 🛠️ - Web search to system control
- **Customizable** 🎨 - Adjust voice and responses
- **Cross-platform** 💻 - Windows/Linux/macOS support

## 📦 Installation

### Prerequisites (For Linux)
```bash
sudo apt-get update && sudo apt-get install -y python3 python3-pip espeak ffmpeg libespeak1
```

### 1. Clone repository
```bash
git clone https://github.com/moeinnm-99/EDITH.git && cd EDITH
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Screenshot setup
```bash
sudo apt install -y gnome-screenshot
```

## 🚀 Usage

### Basic launch
```bash
python3 edith_v0.1.py
```

### Alternative launch methods:
```bash
# Linux/Mac with virtual display
xvfb-run -l python3 edith_v0.1.py

# Windows
python edith_v0.1.py
```

## 🛠️ Configuration

Edit in code:
```python
# Voice settings
engine.setProperty('voice', M_voice_id)  # F_voice_id for female
engine.setProperty('rate', 180)  # 100-200 speed
engine.setProperty('volume', 0.8)  # 0.0-1.0 volume

# Email setup
server.login("your_email@gmail.com", "your_password")
```

## 🌈 Customization

Add custom commands:
```python
elif 'your command' in data:
    # Your code
    speak("Custom response")
```

## 🤝 Contributing

1. Fork repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature`)
5. Open Pull Request

## 📜 License
---


## 👨‍💻 Author

**Moein Nouri**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moein-nouri-62803731a/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/moeinnm_99)

Contributions welcome! Feel free to open issues or submit PRs.

## 🔮 Coming Soon
- New Updates For Edith Comming Soon

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=moeinnm-99&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=moeinnm-99&layout=compact&theme=radical)

Experience cosmic productivity! ✨🚀
