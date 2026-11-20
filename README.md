# 🔍 LensaTalenta — CV Information Extractor

<div align="center">

![LensaTalenta Banner](https://img.shields.io/badge/LensaTalenta-CV%20Extraction%20Engine-00d4f5?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xNS41IDE0aC0uNzlsLS4yOC0uMjdBNi41IDYuNSAwIDAgMCAxNiA5LjVhNi41IDYuNSAwIDAgMC0xMyAwIDYuNSA2LjUgMCAwIDAgNi41IDYuNWMxLjYxIDAgMy4wOS0uNTkgNC4yMy0xLjU3bC4yNy4yOHYuNzlsNSA0Ljk5TDIwLjQ5IDE5bC00Ljk5LTV6bS02IDBDNy4wMSAxNCA1IDExLjk5IDUgOS41UzcuMDEgNSA5LjUgNSAxNCA3LjAxIDE0IDkuNSAxMS45OSAxNCA5LjUgMTR6Ii8+PC9zdmc+)
![Version](https://img.shields.io/badge/Version-2.0-teal?style=for-the-badge)
![Built With](https://img.shields.io/badge/Built%20With-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-blue?style=for-the-badge)
![IBM x Hacktiv8](https://img.shields.io/badge/IBM%20x-Hacktiv8-orange?style=for-the-badge)

**Capstone Project — IBM x Hacktiv8 AI Engineering Bootcamp**

[🚀 Live Demo](#) · [📋 Dokumentasi](#dokumentasi) · [⚡ Fitur](#fitur-utama)

</div>

---

## 📌 Judul Capstone Project

> **LensaTalenta: Intelligent CV Information Extractor for HR Teams**

---

## 🚨 Problem Statement

### Konteks Masalah

Tim HR dan rekruter di perusahaan Indonesia — terutama startup dan korporasi skala menengah-besar — menghadapi tantangan serius dalam proses *talent acquisition*:

- **Volume CV yang membludak**: Satu lowongan kerja bisa menghasilkan ratusan hingga ribuan CV masuk dalam waktu singkat, terutama via platform seperti LinkedIn, Jobstreet, dan Glints.
- **Proses manual yang melelahkan**: HR harus membaca setiap CV satu per satu untuk mengidentifikasi informasi kritis seperti keahlian teknis, pengalaman kerja, dan latar belakang pendidikan — proses yang memakan waktu rata-rata 6–8 menit per CV.
- **Inkonsistensi format CV**: Pelamar menggunakan berbagai format (PDF, Word, desain bebas), sehingga sulit melakukan perbandingan kandidat secara objektif dan terstruktur.
- **Bias tidak disadari (unconscious bias)**: Keputusan penyaringan awal yang bergantung pada penilaian manusia rentan terhadap bias subjektif yang merugikan kandidat yang qualified.
- **Keterlambatan *time-to-hire***: Proses screening yang panjang memperlambat siklus rekrutmen, berisiko kehilangan kandidat terbaik ke kompetitor.

### Yang Terdampak

- **Tim HR & Rekruter**: Menanggung beban kerja administratif tinggi, menyita waktu dari aktivitas bernilai tinggi seperti wawancara mendalam dan *employer branding*.
- **Pelamar Kerja**: Qualified candidates berpotensi tidak terdeteksi akibat keterbatasan waktu review manual.
- **Perusahaan**: Biaya rekrutmen membengkak, posisi kritis terlalu lama kosong (*vacancy cost*), produktivitas tim terganggu.

### Mengapa Penting Diselesaikan

Dengan pertumbuhan pasar kerja digital Indonesia yang pesat dan meningkatnya kompetisi talenta di sektor teknologi, kemampuan memproses CV secara cepat dan akurat menjadi keunggulan kompetitif nyata bagi perusahaan yang ingin mendapatkan kandidat terbaik sebelum kompetitor.

---

## 👥 Target Users

| Segmen | Karakteristik | Kebutuhan |
|---|---|---|
| **HR Manager / Talent Acquisition** | Mengelola proses rekrutmen end-to-end, bekerja di perusahaan 50–5000+ karyawan | Screening CV cepat, laporan kandidat terstruktur, shortlist objektif |
| **Technical Recruiter** | Fokus pada posisi IT/Engineering, harus memahami stack teknologi | Filter berdasarkan tech stack spesifik, keyword matching skill teknis |
| **HR Generalist (Perusahaan Kecil)** | Merangkap banyak tugas, waktu terbatas | Alat simple yang langsung pakai tanpa training, output mudah dipahami |
| **Kepala Departemen Non-HR** | Ikut dalam proses hiring teknis, butuh ringkasan kandidat singkat | Kartu profil visual, skor kecocokan yang mudah dibaca |

---

## 🎯 Potential Impact

### Dampak Langsung
- ⚡ **10x lebih cepat** dalam proses screening awal — dari rata-rata 7 menit/CV menjadi <30 detik/CV
- 📊 **Konsistensi 100%** dalam format output — semua CV dikonversi ke struktur data yang seragam
- 🔍 **Objektivitas lebih tinggi** — penilaian berdasarkan data terstruktur, bukan kesan visual semata
- 💾 **Export CSV siap pakai** — langsung terintegrasi ke spreadsheet atau HRIS yang sudah ada

### Dampak Jangka Panjang
- Pengurangan *cost-per-hire* melalui efisiensi proses
- Peningkatan kualitas shortlist karena kandidat qualified tidak terlewat
- Waktu HR tersalurkan ke aktivitas bernilai tinggi: wawancara, *culture fit assessment*, *employer branding*
- Fondasi data kandidat terstruktur untuk analitik rekrutmen jangka panjang

---

## ⚡ Fitur Utama

### 🔑 Core Features

| Fitur | Deskripsi |
|---|---|
| **📂 PDF & DOCX Real Extraction** | Menggunakan **PDF.js** dan **mammoth.js** untuk membaca teks asli dari file — bukan simulasi, bukan placeholder |
| **⚡ Batch Processing** | Upload ratusan CV sekaligus (multi-file drag & drop), diproses satu per satu dengan indikator progres real-time |
| **🧬 Extraction Engine** | Parser cerdas untuk Nama, Role, Email, Telepon, LinkedIn, Lokasi, Usia, Jenis Kelamin, Tanggal Lahir |
| **⚙ Skills Detection** | Database 80+ hard skills teknologi + 30+ soft skills, auto-detected dari seluruh teks CV |
| **💼 Experience Parser** | Ekstraksi Role, Perusahaan, Durasi (dalam bulan), dengan parser kalender Bahasa Indonesia |
| **🎓 Education Extractor** | Jenjang pendidikan (S1/S2/D3/SMA), nama institusi, tahun, IPK |
| **🔍 Keyword Matching** | Tambah keyword bebas, lihat persentase kecocokan dan skill mana yang match/tidak match |
| **⭐ Role-Fit Score** | Skor otomatis 0–100 berdasarkan kelengkapan profil, kedalaman skill, dan total pengalaman |
| **📋 Raw JSON Output** | Output data terstruktur lengkap, copy satu klik untuk integrasi ke sistem lain |
| **⬇ Export CSV** | Export seluruh kandidat ke `.csv` dengan semua field — siap import ke Excel/Google Sheets/HRIS |

### 🗂 Filter & Search

| Filter | Opsi |
|---|---|
| 🎓 Pendidikan | S1 / S2 / D3 / SMA-SMK |
| 💼 Pengalaman | Fresh (0-12 bln) / 1-3 thn / 3-6 thn / 6+ thn |
| ⭐ Role-Fit Score | Tinggi (≥70) / Menengah (≥45) / Rendah (<45) |
| 🎂 Usia | <25 / 25-30 / 31-35 / 36+ |
| 🔎 Free Text Search | Nama, skill, perusahaan, lokasi — real-time |

---

## 🔄 Alur Sistem

```
┌─────────────────────────────────────────────────────────────┐
│                    LENSA TALENTA SYSTEM FLOW                │
└─────────────────────────────────────────────────────────────┘

  [1] INPUT
  ┌───────────────────┐
  │  Upload File       │  ← PDF, DOCX, DOC (single atau batch)
  │  atau Paste Teks   │  ← Copy-paste langsung
  │  atau Contoh CV    │  ← 2 sample built-in
  └────────┬──────────┘
           │
  [2] TEXT EXTRACTION
  ┌───────────────────┐
  │  PDF.js Parser     │  ← Membaca stream PDF → teks mentah
  │  mammoth.js        │  ← Membaca DOCX → teks bersih
  └────────┬──────────┘
           │
  [3] INFORMATION EXTRACTION ENGINE
  ┌───────────────────────────────────────────────┐
  │  Regex + Keyword DB Parser                    │
  │  ├── Personal Info (nama, email, phone, dsb)  │
  │  ├── Skills (80+ hard + 30+ soft skills DB)   │
  │  ├── Experience (role, company, durasi/bulan) │
  │  ├── Education (jenjang, institusi, IPK)      │
  │  ├── Certifications                           │
  │  └── Role-Fit Score Calculator (0–100)        │
  └────────┬──────────────────────────────────────┘
           │
  [4] KEYWORD MATCHING (Opsional)
  ┌───────────────────┐
  │  Input keyword     │  ← HR input skill/requirement
  │  Match vs CV data  │  ← % kecocokan per kandidat
  └────────┬──────────┘
           │
  [5] OUTPUT & FILTER
  ┌───────────────────────────────────┐
  │  Candidate List (sortable)        │
  │  ├── Kartu Profil Visual          │
  │  ├── Filter: Edu/Exp/Score/Usia   │
  │  ├── Free-text Search             │
  │  ├── Raw JSON (copy 1-klik)       │
  │  └── Export CSV                  │
  └───────────────────────────────────┘
```

---

## 🛠 Tech Stack

| Teknologi | Peran | Keterangan |
|---|---|---|
| **HTML5** | Markup | Semantic, accessible |
| **CSS3** | Styling | Custom properties, Grid, Glassmorphism |
| **Vanilla JavaScript** | Logic | ES6+, Async/Await, Regex engine |
| **PDF.js** (Mozilla) | PDF Parser | Client-side, no server needed |
| **mammoth.js** | DOCX Parser | Client-side Word document reader |
| **GitHub Pages** | Hosting | Static deployment |

> **Zero backend required.** Semua pemrosesan berlangsung 100% di browser user. Data CV tidak pernah dikirim ke server manapun — privasi kandidat terjaga penuh.

---

## 🚀 Cara Menjalankan

### Option 1: Langsung Buka (Recommended)
```bash
# Clone repo
git clone https://github.com/r3conxploit/BOBxHacktiv8-CV-Information-Extractor-Project.git

# Buka di browser
start index.html   # Windows
open index.html    # macOS
```

### Option 2: Live Server (VS Code)
1. Install extension **Live Server** di VS Code
2. Klik kanan `index.html` → **Open with Live Server**

### Option 3: GitHub Pages
Akses langsung: `https://r3conxploit.github.io/BOBxHacktiv8-CV-Information-Extractor-Project/`

---

## 📂 Struktur Project

```
BOBxHacktiv8-CV-Information-Extractor-Project/
│
├── index.html          # Single-page application (semua-dalam-satu)
├── README.md           # Dokumentasi lengkap ini
├── project.json        # Metadata project untuk submission
└── .gitignore          # Git ignore config
```

---

## 🎨 Improvisasi & Inovasi

Dibandingkan pendekatan CV screening tradisional, LensaTalenta menghadirkan:

1. **Real PDF/DOCX Parsing di Browser** — menggunakan PDF.js (Mozilla) dan mammoth.js, file CV dibaca langsung di browser tanpa upload ke server. Privasi data kandidat terjaga 100%.

2. **Batch Processing Ratusan File** — HR bisa upload ratusan CV sekaligus dengan drag & drop multi-file. Engine memproses satu per satu dengan indikator progres real-time.

3. **Intelligent Indonesian Language Parser** — parser kalender Bahasa Indonesia (Januari–Desember), deteksi "Sekarang" sebagai end date, parsing format tanggal lahir Indonesia.

4. **Multi-dimensional Filtering** — kombinasi filter usia + pendidikan + pengalaman + skor + keyword memberikan power query yang setara dengan ATS (Applicant Tracking System) komersial.

5. **Role-Fit Score Algorithm** — skor komposit 0–100 yang mempertimbangkan kelengkapan kontak (20%), kedalaman hard & soft skills (40%), total pengalaman kerja (25%), dan kualitas pendidikan (15%).

6. **Zero-dependency Frontend** — tidak membutuhkan framework berat. Hanya HTML + CSS + JS murni + 2 library parsing. Bisa jalan offline setelah halaman dimuat.

---

## 👨‍💻 Tentang Project

| | |
|---|---|
| **Program** | IBM x Hacktiv8 AI Engineering Bootcamp |
| **Kategori** | Capstone Project — HR Technology |
| **Platform** | Web Application (SPA) |
| **Bahasa UI** | Bahasa Indonesia |
| **Status** | ✅ Completed |

---

## 📄 Lisensi

MIT License — bebas digunakan, dimodifikasi, dan didistribusikan untuk keperluan apapun.

---

<div align="center">

**Dibuat dengan ❤️ menggunakan IBM Bob AI Assistant**

*LensaTalenta — Menemukan talenta terbaik, lebih cepat.*

</div>
