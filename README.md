<div align="center">
  <a href="https://github.com/yuzono/aniyomi-extensions">
    <img src="https://avatars.githubusercontent.com/u/209217388" alt="Yuzono" height="100">
  </a>
  <img src="https://i.ibb.co/Z6kXZ1mc/androidstudio-1024x1024.png" alt="Logo" height="100">
  <a href="https://github.com/keiyoushi/extensions-source">
    <img src="https://avatars.githubusercontent.com/u/113362897" alt="Keiyoushi" height="100">
  </a>

  <h1>Extension Source Builder Using Colab</h1>

  <a href="https://colab.research.google.com/github/mrtear/Extension-Source-Builder/blob/main/Extension_Source_Builder.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="200px"/>
  </a>
</div>

## 🔮 Overview

Extension-Source Builder is a Google Colab notebook designed to easily build APKs from various extension sources (like Keiyoushi and Aniyomi). It allows you to effortlessly configure the Android environment, clone repositories with specific branches, choose languages and sources, and compile extensions entirely in the cloud. Once built, the generated APKs can be easily installed on your device via QR codes.

## ⚡ Features

- **Simple Setup**: Execute cells in sequence to prepare the Android build environment automatically.
- **Clone Repositories**: Target specific repositories and branches on the fly.
- **Build Extensions**: Customize and compile APK extensions without needing Android Studio installed locally.
- **APK Upload**: Generates a temporary download link and QR code for easy sharing and installation.

## 🚀 Quick Start

1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrtear/Extension-Source-Builder/blob/main/Extension_Source_Builder.ipynb)
2. Run the cells in order from top to bottom.

## 🚨 Notes

1. **Colab Free Tier Limits:**
   - **TPU Runtime:** 47GB RAM, 24vCPU | ~3h 20m |
   - **CPU Runtime:** 12GB RAM, 2vCPU | ~12h (closes automatically after ~90 mins of inactivity)
   - *Note: Compiling Android extensions relies entirely on the CPU. Do not select a GPU runtime, as it will not speed up the build and will needlessly consume your Colab compute limits.*

2. **Before Closing:**
   - Properly terminate your session to avoid hitting Colab rate limits. Go to the top menu and select: `Runtime → Disconnect and delete runtime`.
  
## 🔗 Resources
- [Extension Repos Wiki](https://wotaku.wiki/ext/mihon)

---
<p align="center">
  Crafted with ❤️ using AI for the Tachiyomi community by <a href="https://github.com/mrtear">me</a>
</p>
