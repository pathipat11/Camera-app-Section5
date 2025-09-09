# 📸 Camera-app-Section5

A modern camera application built using **React Native** and **Expo** with **TypeScript**. This app allows users to take photos, view the latest photo as a thumbnail, save images to the media library, and browse recent photos in a gallery with a sleek UI.

## ✨ Features

* 📷 **Take Photos** using front or back camera
* 🔦 **Flash Control**: On / Off
* 🖼️ **Thumbnail Preview** of the latest photo
* 🖌️ **Gallery View**: Display up to 50 recent photos
* 💾 **Save to Media Library** instantly
* 🌗 **Modern UI** with rounded buttons, shadows, and gradient effects
* 📱 **Mobile Responsive** optimized for smartphones

## 🎬 Demo Video

Here is a quick GIF showing the app's interface and interactions:

<img src="assets/video/demo-app-camera.gif" alt="App Demo" width="250" />

*Replace `assets/video/demo-app-camera.gif` with your GIF file path.*

## 🛠️ Tech Stack

* React Native
* Expo
* TypeScript
* Expo Camera (`expo-camera`)
* Expo Media Library (`expo-media-library`)
* React Native Vector Icons
* Animated API for button effects

## 🚀 Getting Started

### Prerequisites

* Node.js
* Expo CLI (`npm install -g expo-cli`)

### Create Project

Create a new Expo project using the **blank TypeScript template**:

```bash
npx create-expo-app@latest camera-app --template blank-typescript
```

### Install Required Libraries

To access the camera and media library, install:

```bash
cd camera-app
npx expo install expo-camera expo-media-library
```

> Using `npx expo install` ensures compatibility with your Expo SDK version.

### Running the App

```bash
npx expo start
```

Then scan the QR code with **Expo Go** or use an emulator.

## 🔄 Project Structure

```
camera-app/
├── app/                      # Screens (if using Expo Router)
├── assets/
│   └── video/
│       └── camera-app.gif    # Demo GIF
├── components/               # Optional UI components
├── App.tsx                   # Main App file
├── package.json
└── README.md
```

## 👤 Author

**Pathipat Mattra**

* 🌐 Facebook: [Pathipat Mattra](https://facebook.com/pathipat.mattra)
* 💻 GitHub: [pathipat11](https://github.com/pathipat11)
* 💼 LinkedIn: [Pathipat Mattra](https://linkedin.com/in/viixl)

---

Crafted with ❤️ for the course *Hybrid Mobile Application Programming* (**IN405109**)
**Computer Science, Khon Kaen University**
