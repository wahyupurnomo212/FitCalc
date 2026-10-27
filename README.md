# FitCalc Pro - Kalkulator Kebugaran Tubuh Berbasis Web

**FitCalc Pro** adalah aplikasi web interaktif, modern, dan lengkap untuk menghitung, menganalisis, serta melacak berbagai metrik kesehatan dan kebugaran tubuh secara akurat berdasarkan formula ilmiah medis dan keolahragaan.

Aplikasi ini dapat dijalankan **langsung tanpa memerlukan instalasi server atau dependensi rumit**, cukup dengan membuka file `index.html` atau mengklik ganda `Buka_Aplikasi.bat`.

---

## 🌟 Fitur Utama Aplikasi

### 1. 🚀 Penilaian Lengkap (All-in-One Fitness Assessment)
Cukup isi data profil satu kali (Gender, Usia, Tinggi, Berat, Lingkar Tubuh, Tingkat Aktivitas, Target Sasaran, Pola Diet), sistem akan langsung menganalisis dan menampilkan:
- **Skor Kebugaran Tubuh (Health & Fitness Score 0–100)** dengan indikator status kesehatan.
- **Indeks Massa Tubuh (BMI / IMT)** lengkap dengan grafik jarum visual (*gauge*) dan kategori standar Kemenkes RI / Asia-Pasifik.
- **Kebutuhan Kalori Harian (BMR & TDEE)** serta target kalori sesuai sasaran (menurunkan berat badan, mempertahankan, atau meningkatkan massa otot).
- **Distribusi Makronutrisi Interaktif** (Target Gram & Kalori Karbohidrat, Protein, dan Lemak Sehat) divisualisasikan dalam grafik donat Chart.js.
- **Estimasi Persentase Lemak Tubuh (U.S. Navy Method)** serta pembagian Massa Lemak (*Fat Mass*) vs Massa Bebas Lemak (*Lean Body Mass*).
- **Kebutuhan Hidrasi Harian** (Liter dan estimasi jumlah gelas air).
- **Zona Denyut Jantung Latihan** (Zona Pembakaran Lemak / Fat Burn Zone & Max HR).
- **Rekomendasi Terpersonalisasi** berisi tips nutrisi, pola makan, dan latihan fisik yang disesuaikan secara dinamis dengan hasil fisik Anda.

---

### 2. 🧮 Modul Kalkulator Khusus (Mandiri)
Setiap modul juga dapat digunakan secara terpisah:
- **⚖️ Kalkulator BMI & Berat Badan Ideal**:
  - Perbandingan 4 formula ilmiah: Standar Asia Pasifik Kemenkes RI, Rumus Broca, Rumus Devine (1974), dan Rumus Robinson (1983).
  - Tabel edukasi klasifikasi BMI Kemenkes RI beserta tingkat risikonya.
- **🔥 Kalkulator BMR, TDEE & Macro Planner**:
  - Formula Mifflin-St Jeor dengan 5 tingkat aktivitas fisik.
  - Pilihan rasio diet: Gizi Seimbang, Tinggi Protein, Rendah Karbohidrat (Low Carb), dan Ketogenik.
- **📏 Kalkulator Persentase Lemak Tubuh (U.S. Navy)**:
  - Berdasarkan lingkar leher, pinggang, pinggul (wanita), tinggi dan berat badan.
  - Klasifikasi standar American Council on Exercise (ACE).
  - Panduan posisi pengukuran lingkar tubuh yang tepat.
- **💧 Kebutuhan Hidrasi & Tracker Air Harian**:
  - Perhitungan kebutuhan air sesuai berat badan dan durasi latihan harian.
  - **Pencatat Minum Interaktif**: Klik gelas untuk menandai asupan air minum Anda setiap hari (tersimpan otomatis).
- **❤️ Target Denyut Jantung & 5 Zona Kardio**:
  - Formula Karvonen & Cadangan Jantung (*Heart Rate Reserve*).
  - Pembagian 5 zona: *Active Recovery*, *Fat Burn*, *Aerobic Fitness*, *Anaerobic Threshold*, dan *VO2 Max Peak*.
- **🏋️ Kalkulator Kekuatan 1 Rep Max (1RM)**:
  - Formula Epley & Brzycki untuk latihan beban di gym.
  - Tabel panduan beban angkatan: 95% (kekuatan maksimal), 85% (densitas otot), 75% (hipertrofi otot), 65% (endurance).

---

### 3. 📊 Riwayat & Pelacak Kemajuan (Progress Tracker)
- Data evaluasi dapat disimpan ke memori browser (**LocalStorage**).
- **Grafik Tren Garis Perkembangan**: Memantau penurunan berat badan dan perubahan BMI secara visual dari waktu ke waktu.
- **Tabel Riwayat Lengkap**: Menyimpan tanggal, berat, BMI, kalori, lemak tubuh, dan skor kebugaran.
- **Ekspor Data ke CSV**: Unduh data riwayat untuk dibuka di Microsoft Excel atau Google Sheets.
- **Cetak / Ekspor Laporan PDF**: Format cetak bersih siap pakai untuk dokumentasi atau konsultasi dokter/pelatih kebugaran.

---

### 4. 🎨 Desain & Pengalaman Pengguna (UI/UX)
- **Mode Gelap (Dark Mode) & Mode Terang (Light Mode)**: Otomatis mendeteksi preferensi sistem dan dapat diganti secara instan.
- **Tampilan Responsif**: Nyaman digunakan di layar komputer (desktop), laptop, tablet, maupun smartphone (ponsel).
- **Desain Modern Glassmorphism & Micro-Interactions**: Transisi halus, animasi interaktif, dan palet warna profesional.

---

## 📁 Struktur Berkas

```text
Latihan/
├── index.html           # Struktur utama antarmuka pengguna (HTML5 & Tailwind CSS)
├── Buka_Aplikasi.bat    # Shortcut sekali klik untuk membuka aplikasi di browser
├── README.md            # Dokumentasi lengkap aplikasi
├── css/
│   └── style.css        # Gaya kustom, glassmorphism, animasi jarum gauge, & format print PDF
└── js/
    ├── calculators.js   # Modul algoritma dan formula ilmiah kebugaran
    ├── charts.js        # Modul visualisasi grafik Chart.js (Donat, Garis, Batang)
    ├── history.js       # Modul penyimpanan LocalStorage & ekspor CSV
    └── app.js           # Pengendali UI, event listeners, tracker hidrasi, & tema
```

---

## 🚀 Cara Menjalankan Aplikasi

1. **Cara Paling Cepat**:
   - Klik ganda (double-click) berkas `Buka_Aplikasi.bat` di dalam folder ini.
   - Atau klik kanan `index.html` -> pilih **Open with** -> pilih browser favorit Anda (Google Chrome, Microsoft Edge, Mozilla Firefox, dll).
2. Selesai! Aplikasi langsung aktif dan dapat digunakan secara offline maupun online.
