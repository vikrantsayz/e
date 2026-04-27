# 🏫 EduManage Pro — Android App

[![Build APK](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build.yml/badge.svg)](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build.yml)

Advanced School Management System — Android WebView App  
Built around [EduManage Pro v3.0](https://itsvkrnt.github.io/f/) by @vikrantsayz

---

## 📱 App Features

| Feature | Detail |
|---|---|
| 🔄 Pull to Refresh | Swipe down to reload |
| 📶 Offline Detection | Beautiful offline screen with retry |
| ⬅️ Back Navigation | Hardware back navigates in-app |
| 📁 File Upload | Supports file chooser for uploads |
| 📥 Download Support | Opens downloads via browser |
| 🔔 Notifications | Permission handled automatically |
| 📞 Deep Links | tel:, mailto:, WhatsApp all work |
| 💫 Splash Screen | Animated launch screen |
| 🌙 Dark Mode | Follows system theme |
| 🔒 HTTPS Only | No cleartext traffic |

---

## 🚀 How to Get the APK

### Option 1: GitHub Actions (EASIEST — Recommended)

1. Push this folder to a GitHub repo
2. Go to **Actions** tab
3. Click the latest **"Build EduManage Pro APK"** run
4. Scroll down to **Artifacts**
5. Download **EduManagePro-v3.0-debug**
6. Unzip → install the `.apk` on your phone ✅

### Option 2: Android Studio (Local Build)

1. Open this folder in Android Studio
2. Wait for Gradle sync
3. Click **Build → Build Bundle(s)/APK(s) → Build APK(s)**
4. APK saved to `app/build/outputs/apk/debug/`

---

## 📲 Installing the APK

1. Transfer APK to your Android phone
2. Go to **Settings → Security → Install Unknown Apps**
3. Enable for your file manager/browser
4. Tap the APK → Install ✅

---

## 📦 Project Structure

```
EduManagePro/
├── .github/workflows/build.yml     ← Auto-builds APK
├── app/src/main/
│   ├── java/com/vkrnt/edumanage/
│   │   ├── MainActivity.kt         ← Main WebView logic
│   │   └── SplashActivity.kt       ← Splash screen
│   ├── res/
│   │   ├── layout/                 ← UI layouts
│   │   ├── drawable/               ← Icons & images
│   │   └── values/                 ← Colors, strings
│   └── AndroidManifest.xml
└── build.gradle
```

---

Built with ❤️ for **@vikrantsayz**
