<p align="center">
  <img src="assets/icon.png" width="150"/>
</p>

# 📍 CheckInKu Pro

## 🚀 Release Candidate — React Native Expo + EAS Build

CheckInKu Pro merupakan aplikasi mobile berbasis **React Native Expo** yang memanfaatkan fitur native smartphone seperti kamera, galeri, GPS, permission system, dan layanan cuaca.

Aplikasi ini digunakan untuk melakukan proses **check-in digital** dengan mengambil foto, memperoleh lokasi pengguna secara real-time, menampilkan koordinat GPS, informasi lokasi, serta informasi cuaca berdasarkan lokasi pengguna.

Project ini dikembangkan sebagai implementasi:

**Misi 14 — Menyiapkan Aplikasi untuk Rilis (Release Candidate)**  
**Praktik Pemrograman Mobile (React Native)**  
**Universitas Prima Indonesia**

Tahapan pengembangan meliputi:

- Konfigurasi aplikasi menggunakan Expo.
- Pengaturan app.json.
- Pembuatan custom icon dan splash screen.
- Konfigurasi EAS Build.
- Pembuatan Android APK.
- Instalasi APK pada perangkat Android tanpa Expo Go.


---

# 📱 Fitur Utama Aplikasi

## 📸 Camera Check-In

Aplikasi menggunakan kamera smartphone untuk mengambil foto sebagai dokumentasi aktivitas check-in.

Implementasi:

- Meminta izin kamera.
- Membuka kamera perangkat.
- Mengambil foto menggunakan kamera.
- Menampilkan hasil foto pada aplikasi.


---

## 🖼 Gallery Integration

Pengguna dapat memilih foto dari galeri perangkat.

Implementasi:

- Meminta izin akses galeri.
- Membuka penyimpanan gambar perangkat.
- Memilih foto.
- Menampilkan foto pilihan pengguna.


---

## 📍 GPS Location

Aplikasi menggunakan GPS perangkat untuk mendapatkan lokasi pengguna.

Informasi yang ditampilkan:

- Latitude.
- Longitude.
- Nama lokasi.
- Informasi lokasi berdasarkan koordinat GPS.


---

## 🌤 Weather Information

Aplikasi menampilkan informasi cuaca berdasarkan lokasi pengguna.

Fitur:

- Mengambil koordinat lokasi pengguna.
- Menghubungkan lokasi dengan layanan cuaca.
- Menampilkan kondisi cuaca berdasarkan lokasi.


---

# 🔐 Native Permission System

Aplikasi menerapkan sistem permission native Android.

Permission yang digunakan:

### CAMERA

Digunakan untuk mengambil foto check-in melalui kamera perangkat.

### READ_MEDIA_IMAGES

Digunakan untuk memilih foto dari galeri.

### ACCESS_FINE_LOCATION

Digunakan untuk mendapatkan lokasi pengguna melalui GPS.

Apabila permission ditolak, aplikasi tetap berjalan tanpa mengalami crash.


---

# 📦 Release Build Information

## EAS Build Configuration

Aplikasi dikonfigurasi menggunakan:

- Expo Application Services (EAS)
- EAS CLI
- Android APK Build


Build Profile:

```
preview
```


Output:

```
Android APK
```


Perintah build:

```bash
eas build --platform android --profile preview
```


Status Build:

```
FINISHED ✅
```


---

# 📥 APK Installation

APK hasil build dapat di-install langsung pada perangkat Android tanpa menggunakan Expo Go.


## 🔗 EAS Build Link

https://expo.dev/accounts/ruthangelsitorus/projects/checkinku-pro/builds/dd0f45fe-e5ed-43ba-b4ab-03b33c427bbf


Link tersebut merupakan halaman EAS Build yang berisi hasil build APK dan tombol instalasi.


---

# 🎨 Build Assets

Aplikasi menggunakan asset custom untuk kebutuhan release.


## App Icon

File:

```
assets/icon.png
```

Spesifikasi:

- Format PNG.
- Ukuran 1024 × 1024 px.
- Desain khusus aplikasi CheckInKu Pro.


## Adaptive Icon

File:

```
assets/adaptive-icon.png
```

Digunakan sebagai icon launcher Android dengan logo berada di tengah dan memiliki padding.


## Splash Screen

File:

```
assets/splash.png
```

Digunakan sebagai tampilan awal aplikasi ketika dibuka.

Background color:

```
#0A84FF
```


---

# 📸 Screenshot Bukti Aplikasi

Dokumentasi proses build, instalasi, dan penggunaan aplikasi:


## 1. EAS Build Finished

![EAS Build Finished](screenshots/01_eas_build_finished.jpeg)


## 2. EAS Dashboard Build

![EAS Dashboard Build](screenshots/02_eas_dashboard_finished.jpeg)


## 3. Instalasi APK

![APK Installation](screenshots/03_install_apk.jpeg)


## 4. Struktur Project

![Project Structure](screenshots/04_project_structure.jpeg)


## 5. Splash Screen Aplikasi

![Splash Screen](screenshots/05_splash_screen_aplikasi.jpeg)


## 6. Permission Screen

![Permission Screen](screenshots/06_home_permission_screen.jpeg)


## 7. Check-In Camera & Location

![Check In Camera Location](screenshots/07_checkin_camera_location_screen.jpeg)


## 8. Icon Aplikasi Home Screen

![Application Icon](screenshots/08_app_icon_home_screen.jpeg)


---

# 🛠 Tech Stack

Teknologi yang digunakan:

- React Native
- Expo
- JavaScript
- Expo Image Picker
- Expo Location
- AsyncStorage
- Linking API
- Open-Meteo Weather API
- Expo Application Services (EAS)


---

# ▶️ Cara Menjalankan Project

## Clone Repository

```bash
git clone https://github.com/ruthangll/CheckInKu-Pro-Release.git
```


## Masuk Folder Project

```bash
cd CheckInKu-Pro-Release
```


## Install Dependency

```bash
npm install
```


## Jalankan Project

```bash
npx expo start
```


Aplikasi dapat dijalankan menggunakan:

- Expo Go.
- Android APK hasil EAS Build.


---

# 🔗 Expo Snack

Versi interaktif aplikasi dapat dicoba melalui Expo Snack:

https://snack.expo.dev/@ruthangelsitorus/checkinku-proo


---

# 📂 Struktur Project

```
CheckInKu-Pro-Release
│
├── App.js
├── app.json
├── eas.json
├── package.json
├── README.md
│
├── assets
│   ├── icon.png
│   ├── adaptive-icon.png
│   └── splash.png
│
└── screenshots
    ├── 01_eas_build_finished.jpeg
    ├── 02_eas_dashboard_finished.jpeg
    ├── 03_install_apk.jpeg
    ├── 04_project_structure.jpeg
    ├── 05_splash_screen_aplikasi.jpeg
    ├── 06_home_permission_screen.jpeg
    ├── 07_checkin_camera_location_screen.jpeg
    └── 08_app_icon_home_screen.jpeg
```


---

# 👩‍💻 Developer

**Ruth Angel Sitorus**

Universitas Prima Indonesia

Mata Kuliah:

**Praktek Pemrograman Mobile (React Native)**


Project:

**CheckInKu Pro**


Mission:

**Misi 14 — Menyiapkan Aplikasi untuk Rilis (Release Candidate)**