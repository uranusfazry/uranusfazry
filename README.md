# 🌌 Uranus Fazry — Web & App Digital Creator

![Banner](https://uranusfazry.vercel.app/banner.png)

> 🚀 **Personal Portfolio & Portal App** — Showcase of projects, tools, and interactive features.

---

## 📊 Status & Stats

![GitHub stars](https://img.shields.io/github/stars/uranusfazry/uranusfazry?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/uranusfazry/uranusfazry?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/uranusfazry/uranusfazry?style=for-the-badge)
![GitHub PRs](https://img.shields.io/github/issues-pr/uranusfazry/uranusfazry?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/uranusfazry/uranusfazry?style=for-the-badge)
![Vercel Deploy](https://therealsujitk-vercel-badge.vercel.app/?app=uranusfazry)

---

## ✨ Overview

**Uranus Fazry** adalah proyek portofolio interaktif yang menampilkan karya, layanan, dan kemampuan saya sebagai **Web & App Digital Creator**.  
Website ini dibangun dengan fokus pada:

- **⚡ Kecepatan** – Memastikan loading super cepat.
- **📱 Responsif** – Tampilan optimal di semua perangkat.
- **🧩 Fleksibilitas** – Pengguna bisa menambah portal, mengatur tampilan, dan menyesuaikan background.
- **🎨 Kreativitas** – Memberi kebebasan desain UI yang bisa dipersonalisasi.

🔗 **Live Demo:** [uranusfazry.vercel.app](https://uranusfazry.vercel.app)

---

## 🎥 Demo & Preview

| Desktop Preview | Mobile Preview |
|-----------------|----------------|
| ![Preview Desktop](https://uranusfazry.vercel.app/preview-desktop.gif) | ![Preview Mobile](https://uranusfazry.vercel.app/preview-mobile.gif) |

*(GIF ini akan menunjukkan interaksi pengguna saat membuat portal, mengubah background, dan melihat hasilnya secara live.)*

---

## 🛠️ Tech Stack

| Layer          | Tools & Frameworks |
|---------------|------------------|
| **Frontend**  | Next.js 14, React 18, Tailwind CSS |
| **Backend**   | Vercel Serverless Functions |
| **Database**  | Supabase / Firebase (opsional) |
| **Icons & UI**| shadcn/ui, Lucide Icons |
| **Deployment**| Vercel (CI/CD otomatis) |
| **Version**   | `v6.0.0-no-pdf` |

---

## 📸 Features

- 🌀 **Dynamic Portals** — Tambah, edit, hapus portal untuk menghubungkan proyek dan tools.
- 🎨 **Customizable UI** — Pilih background, warna, dan icon sesuai preferensi.
- 📦 **Data Backup & Restore** — Simpan data portal ke file JSON dan impor kembali.
- ⚡ **Fast & Responsive** — Desain modern yang mobile-friendly dan ringan.
- 🛡️ **Safe System Reset** — Reset semua data ke default dengan aman.
- 🖼️ **Media Upload Support** — Upload gambar untuk personalisasi tampilan.
- 🌙 **Dark/Light Mode** — Tema otomatis mengikuti sistem.

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/uranusfazry/uranusfazry.git
cd uranusfazry
2️⃣ Install Dependencies
bash
Copy code
npm install
3️⃣ Setup Environment Variables
Buat file .env.local dan isi variabel berikut (opsional jika pakai database):

env
Copy code
NEXT_PUBLIC_SUPABASE_URL=https://xxxx.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=xxxx
4️⃣ Run Development Server
bash
Copy code
npm run dev
Akses di http://localhost:3000

5️⃣ Build for Production
bash
Copy code
npm run build
npm start
📂 Project Structure
csharp
Copy code
uranusfazry/
├── app/                # Next.js App Router pages
│   ├── layout.tsx      # Layout global
│   ├── page.tsx        # Halaman utama
│   └── api/            # Serverless API routes
├── components/         # Komponen UI reusable
├── lib/                # Helper dan utils
├── public/             # Asset statis (icon, gambar)
├── styles/             # Tailwind config & global styles
└── package.json        # Dependencies & scripts
🧪 Testing & QA
✅ Unit Testing: Jest + React Testing Library

✅ Integration Testing: Playwright (opsional)

✅ CI/CD: Otomatis build & deploy via Vercel

Jalankan test lokal:

bash
Copy code
npm run test
🌎 Deployment
Repo ini sudah terhubung ke Vercel, jadi setiap commit ke main akan otomatis ter-deploy.
Kamu juga bisa deploy manual dengan perintah:

bash
Copy code
vercel --prod
🤝 Contributing
Kami terbuka untuk kontribusi!

Fork repo ini

Buat branch baru: git checkout -b feature/fitur-baru

Lakukan perubahan & commit: git commit -m 'Tambah fitur baru'

Push ke branch: git push origin feature/fitur-baru

Buat Pull Request

🧭 Roadmap
 Tambahkan sistem autentikasi pengguna

 Integrasi database real-time (Supabase)

 Fitur share portal ke media sosial

 Tambah mode animasi background

 Optimasi SEO & PWA support

🧑‍💻 Author
Uranus Fazry
🌐 Website: uranusfazry.vercel.app
💼 LinkedIn: linkedin.com/in/uranusfazry
🐦 Twitter/X: @uranusfazry

📜 License
This project is licensed under the MIT License – feel free to use, modify, and share.

© 2025 Uranus Fazry. All Rights Reserved.

yaml
Copy code

---

✅ **Apa yang berbeda dari versi sebelumnya:**  
- 🎥 Tambah **preview section** dengan contoh GIF (desktop & mobile).  
- 🧪 Tambah bagian **Testing & QA** + perintah menjalankan test.  
- 🧭 Tambah **Roadmap** supaya pengunjung tahu rencana pengembangan ke depan.  
- 🌎 Tambah detail **Deployment** (Vercel CI/CD).  
- 🔑 Tambah **setup environment variables** agar developer lain bisa jalankan dengan mudah.  
- Lebih panjang, lebih detail, dan terlihat serius sebagai proyek open-source.  

---

Mau saya buatkan **GIF preview (demo interaktif)** supaya kamu bisa langsung taruh link GIF di README ba
