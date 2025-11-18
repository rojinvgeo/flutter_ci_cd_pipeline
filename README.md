# Flutter CI/CD Pipeline - Internal Testing

This repository demonstrates a **CI/CD pipeline for Flutter** that automates the build of **internal testing APKs** using GitHub Actions.  
No keystore, no Fastlane, and no Java are required — perfect for internal distribution to testers.

---

## 🔹 Features

- Automated build of **debug APK** and **unsigned release APK**  
- Workflow triggers on **push to master** branch or pull requests  
- **Artifacts uploaded** to GitHub Actions for internal testing  
- **Flutter analyzer** and **tests** run automatically  
- Simple setup without keystore or signing  

---

---

## 🔹 How It Works

1. Push your code to the **master** branch.  
2. GitHub Actions workflow triggers automatically.  
3. Flutter dependencies are installed (`flutter pub get`).  
4. Code is analyzed (`flutter analyze`) and tests are run (`flutter test`).  
5. APKs are built:  
   - `app-debug.apk`  
   - `app-release.apk` (unsigned)  
6. APKs are uploaded as **workflow artifacts** for download.

---

## 🔹 How to Download Internal Testing APK

1. Go to **GitHub → Actions → Latest Workflow Run**  
2. Scroll down to **Artifacts**  
3. Download **`ci_cd_app_builds`**  
4. Install APK on your Android device (debug or unsigned release)  

---

## 🔹 What I Learned

- Setting up **GitHub Actions** for Flutter projects  
- Automating **APK builds** for internal testing  
- Uploading build artifacts for **easy distribution**  
- Understanding **branch triggers** and workflow YAML  
- Basics of **CI/CD for Flutter apps**  

---

## 🔹 Notes

- No keystore or signing required for **internal testing builds**  
- For Play Store uploads or signed builds, additional configuration is needed  
- Compatible with Flutter stable channel  

---

## 🔹 References

- [GitHub Actions Documentation](https://docs.github.com/en/actions)  
- [Flutter CI/CD Guide](https://docs.flutter.dev/deployment/ci)

  



