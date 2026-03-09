<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=🎙️%20Voice%20Aura%20v1.0&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Real-time%20Voice%20AI%20%7C%20Gemini%20API%20%7C%20Vite%20%2B%20TypeScript&descAlignY=58&descSize=16" width="100%"/>

[![Build](https://img.shields.io/badge/build-passing-00ffcc?style=flat-square&logo=github)](https://github.com/tabrezahmed51/Voice-Aura-v1.0)
[![Version](https://img.shields.io/badge/version-1.0-ff9f43?style=flat-square)](https://github.com/tabrezahmed51/Voice-Aura-v1.0/releases)
[![License](https://img.shields.io/badge/license-MIT-3a86ff?style=flat-square)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-98.4%25-3178c6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Stars](https://img.shields.io/github/stars/tabrezahmed51/Voice-Aura-v1.0?style=social)](https://github.com/tabrezahmed51/Voice-Aura-v1.0/stargazers)

**[🔗 Live Preview](https://ai.studio/apps/ef5ab480-df21-431e-8981-0a4588886a40) · [🐛 Report Bug](https://github.com/tabrezahmed51/Voice-Aura-v1.0/issues) · [✨ Request Feature](https://github.com/tabrezahmed51/Voice-Aura-v1.0/issues)**

</div>

---

## 📌 Overview

**Voice Aura v1.0** is a browser-native voice interaction app built inside **Google AI Studio**. It connects directly to the **Gemini API** for real-time, low-latency conversational AI — no backend server required.

A production-ready TypeScript starter for developers building voice AI experiences on the web.

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🎤 | **Voice Interaction** | Speak naturally and receive instant AI responses |
| ⚡ | **Gemini-Powered** | Google's latest multimodal LLM under the hood |
| 🌐 | **100% Web-Based** | Zero installs — runs entirely in the browser |
| 🔧 | **Vite + TypeScript** | Lightning-fast HMR dev environment |
| 🎨 | **Themeable UI** | Fully customisable colour palette and layout |
| 🔒 | **Secure Config** | API keys via `.env.local` — never hard-coded |
| 📊 | **Analytics Ready** | Built-in hooks for usage tracking & metrics |
| 🚀 | **One-Click Deploy** | Native Google AI Studio deployment support |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | TypeScript 5.x, Vite 5.x |
| **AI Engine** | Google Gemini API |
| **Voice Capture** | Web Speech API (browser-native) |
| **Runtime** | Node.js ≥ 18 |
| **Deployment** | Google AI Studio |

---

## 📐 System Architecture

```
Browser Client  ──▶  Web Speech API  ──▶  Gemini API  ──▶  AI Studio
(Vite + TS)          (Voice Capture)      (AI Response)    (Deployment)
```

---

## 📂 Folder Structure

```
Voice-Aura-v1.0/
├── src/
│   ├── components/
│   │   ├── VoiceButton.tsx       # Mic trigger button
│   │   ├── Waveform.tsx          # Animated audio waveform
│   │   └── ResponseCard.tsx      # AI response display
│   ├── services/
│   │   ├── gemini.ts             # Gemini API client
│   │   └── speech.ts             # Web Speech API wrapper
│   ├── hooks/
│   │   ├── useVoice.ts           # Voice recording logic
│   │   └── useGemini.ts          # Gemini response handler
│   ├── utils/
│   │   ├── config.ts             # Env vars loader
│   │   └── analytics.ts          # Usage tracking helpers
│   ├── styles/
│   │   ├── globals.css           # Global styles
│   │   └── theme.css             # Colour palette variables
│   ├── App.tsx                   # Root component
│   └── main.ts                   # App entry point
├── public/
│   ├── header-image-16x9.png     # Hero banner
│   └── favicon.ico
├── dist/                         # Production build output
├── index.html                    # HTML entry shell
├── vite.config.ts                # Vite configuration
├── tsconfig.json                 # TypeScript config
├── package.json                  # Dependencies & scripts
├── .env.local                    # 🔒 API key (not committed)
├── .env.example                  # Safe template for contributors
├── .gitignore
└── README.md
```

---

## ⚙️ Prerequisites

- **Node.js** ≥ 18.x
- **npm** ≥ 9.x
- A valid **Gemini API key** — [Get one free →](https://aistudio.google.com/app/apikey)

---

## 🚀 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/tabrezahmed51/Voice-Aura-v1.0.git
cd Voice-Aura-v1.0

# 2. Install dependencies
npm install

# 3. Configure your Gemini API key
echo "GEMINI_API_KEY=your_api_key_here" > .env.local

# 4. Start the development server
npm run dev

# 5. Build for production
npm run build
```

> ⚠️ **Never commit `.env.local`** — ensure it is listed in `.gitignore`.

---

## 🌍 Deployment

| Platform | Status | Notes |
|---|---|---|
| Google AI Studio | ✅ Native | Recommended — zero config |
| Vercel | ✅ Compatible | `npm run build` → deploy `dist/` |
| Netlify | ✅ Compatible | Drag & drop `dist/` folder |
| Cloudflare Pages | ✅ Compatible | Connect repo, set build command |

**[🔗 View Live Preview on AI Studio →](https://ai.studio/apps/ef5ab480-df21-431e-8981-0a4588886a40)**

---

## 🤝 Contributing

Contributions are welcome!

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

Then open a **Pull Request** with a clear description of your changes.
Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

## 👨‍💻 Author

**Tabrez Ahmed** — [@tabrezahmed51](https://github.com/tabrezahmed51)

Built with ❤️ using Google Gemini API & Google AI Studio.

---

## 📜 License

Released under the **[MIT License](LICENSE)** — free to fork, modify, and distribute.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

**Voice Aura v1.0** · Made with ❤️ by [Tabrez Ahmed](https://github.com/tabrezahmed51)

</div>
