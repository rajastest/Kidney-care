# Kidney Care – Android APK project

## Easiest: build online (no installs)
1. Create a free GitHub account and a new repository.
2. Upload ALL files of this folder (including the hidden .github folder).
3. Open the repo > Actions tab > "Build APK" > wait ~5 minutes.
4. Open the finished run > Artifacts > download KidneyCare-APK (zip) > extract app-debug.apk.
5. Copy to the phone, tap it, allow "install unknown apps".

## Or build on a PC
Install Node 20, JDK 17, Android Studio, then:
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android   # Build > Build APK(s)
