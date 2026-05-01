# 🌐 IP & UA Monitor Pro - Ultimate Edition

![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Platform](https://img.shields.io/badge/Platform-GitHub%20Pages-orange.svg)

**IP & UA Monitor Pro** adalah dashboard monitoring koneksi real-time yang dirancang khusus untuk kebutuhan *multi-accounting* dan manajemen sesi web. Tool ini memastikan setiap koneksi yang Anda gunakan aman, fresh, dan terlacak dengan akurasi tinggi.

---

## 🚀 Fitur Unggulan

### 1. 🕒 Dual Real-Time Clock & Date
Memantau dua zona waktu sekaligus dalam satu layar:
*   **Waktu Indonesia (WIB):** Memastikan jadwal kerja lokal tetap on-time.
*   **Waktu Lokasi IP:** Otomatis mendeteksi zona waktu berdasarkan IP yang digunakan (sangat berguna untuk operasional server luar negeri).

### 2. ⚡ Latency (Ping) Indicator
Indikator kecepatan koneksi otomatis (setiap 5 detik):
*   🟢 **0-150ms:** Koneksi sangat stabil.
*   🟡 **151-400ms:** Koneksi rata-rata.
*   🔴 **>400ms:** Koneksi lemot/gangguan.

### 3. 🛡️ Dual Validation (IP & User Agent)
Sistem cerdas yang mengecek database secara real-time:
*   **IP Freshness:** Mendeteksi apakah IP sudah pernah digunakan sebelumnya.
*   **UA Tracker:** Mendeteksi apakah identitas browser (User Agent) sudah pernah dipakai, guna menghindari *flagging* akun.

### 4. 📊 Google Sheets Integration
Semua riwayat koneksi tersimpan otomatis ke Google Sheets, mencakup:
*   Waktu (Timestamp)
*   IP Address & ISP
*   Lokasi Detail (Kota & Negara)
*   User Agent (Identitas Browser)

### 5. 🔗 Quick Access Menu
Akses cepat ke berbagai domain kerja:
*   **Stake RU** (Rusia) & **Stake TR** (Turki).
*   **Speedtest** (via Fast.com).
*   **Cek Kode Pos** terintegrasi pencarian Google.

---

## 🛠️ Cara Instalasi

1.  **Fork atau Salin** kode `index.html` ke repository GitHub Anda.
2.  **Siapkan Database:**
    *   Buat Google Sheets baru.
    *   Buka **Extensions > Apps Script**, lalu tempel kode script `.gs` yang disediakan.
    *   Deploy sebagai **Web App** (akses: Anyone).
3.  **Hubungkan:** Salin URL Web App dari Google Script ke variabel `GOOGLE_SCRIPT_URL` di file HTML.
4.  **Aktifkan GitHub Pages:** Masuk ke Settings Repo > Pages > Pilih Branch Main/Master.

---

## 📸 Preview Interface

*   **Dark Mode UI:** Nyaman di mata untuk kerja durasi lama.
*   **Status Grid:** Kotak indikator Merah/Hijau yang mencolok untuk keamanan instan.
*   **Responsive Table:** Tabel histori yang rapi dengan fitur *hover* untuk melihat User Agent lengkap.

---

## ⚠️ Disclaimer
Project ini dibuat untuk tujuan efisiensi manajemen data pribadi dan monitoring koneksi. Gunakan secara bijak dan pastikan Anda mematuhi kebijakan layanan pihak ketiga yang Anda akses melalui tool ini.

---

**Dibuat dengan ❤️ untuk produktivitas maksimal.**
