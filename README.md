# ibm_capstone_escope
Klasifikasi &amp; ringkasan opini audit, risiko kredit, dan nilai perusahaan berbasis NLP
# Enhanced Summarization & Classification of Audit Opinion, Credit Performance, and Company Evaluation

**Author:** [Valentina Putri](https://linkedin.com/in/valentinaputri)  
**Repository:** [GitHub - valentinaaptr](https://github.com/valentinaaptr)

---

## 🧠 Overview

Proyek ini dirancang untuk mengeksplorasi potensi penggunaan model bahasa besar **IBM Granite (13B-Instruct)** dalam menganalisis teks laporan keuangan dan tahunan perusahaan secara otomatis. Model ini digunakan untuk:

- **Klasifikasi opini audit** (misalnya: wajar tanpa pengecualian, wajar dengan pengecualian, dll.)
- **Deteksi indikasi going concern** berdasarkan narasi auditor
- **Summarization** (ringkasan) opini audit agar lebih mudah dipahami
- **Evaluasi risiko kredit dan nilai perusahaan**, dengan menggabungkan output klasifikasi dan ringkasan dengan **rasio keuangan**:  
  - Debt to Equity Ratio (DER)  
  - Current Ratio  
  - Interest Coverage Ratio (ICR)  
  - Price to Book Value (PBV)

Proyek ini membuktikan bahwa teknologi NLP dapat menggantikan proses manual dalam membaca dan menafsirkan opini auditor, mempercepat proses analisis, dan menghasilkan output yang siap dipakai untuk pengambilan keputusan.

---

## 🎯 Objective

- Menyediakan ringkasan dan klasifikasi opini auditor untuk mempermudah pemahaman laporan tahunan
- Menyediakan insight cepat untuk publik dan investor tanpa harus membaca keseluruhan laporan
- Membantu auditor dan akuntan dalam **benchmarking** dan evaluasi kualitas pengungkapan
- Memberikan analisis tekstual yang terstruktur berbasis **Natural Language Processing (NLP)**

---

## 📊 Dataset

Proyek ini menggunakan **data publik** dari Bursa Efek Indonesia (IDX). Terdiri dari dua jenis data utama:

1. **Teks Opini Audit**
   - Narasi dari auditor independen, termasuk potensi going concern.
   - Digunakan sebagai input klasifikasi opini dan deteksi risiko keberlanjutan usaha.

2. **Data Rasio Keuangan**
   - Diambil dari laporan keuangan tahunan (balance sheet & income statement).
   - Rasio yang dianalisis: DER, Current Ratio, ROE, ICR, PBV.
   - Digunakan untuk mengevaluasi kesehatan dan nilai perusahaan.

### Cara Akses Data
1. Buka: [https://www.idx.co.id](https://www.idx.co.id)  
2. Masuk ke menu **Perusahaan Tercatat > Laporan Keuangan dan Tahunan**  
3. Cari berdasarkan **kode emiten** (contoh: `KREN`) dan pilih tahun laporan

---

## 🔧 Teknologi & Tools

- **Model NLP:** IBM Granite 13B Instruct
- **Platform:** Google Colab
- **API Integration:** Replicate for LLM deployment
- **Bahasa Pemrograman:** Python

---

## 📝 Output

Output dari proyek ini berupa:

- Kategori opini audit (automated classification)
- Indikasi going concern
- Ringkasan teks auditor
- Evaluasi potensi risiko kredit
- Analisis hubungan dengan nilai perusahaan (PBV)

Semua hasil tersebut dapat dijadikan dasar analisis lanjutan oleh analis keuangan, akuntan, maupun pengambil kebijakan investasi.

---

## 🤝 Let’s Connect

Jika kamu tertarik dengan proyek ini, ingin berkolaborasi, atau sekadar berdiskusi:

📩 **Reach out via:** [LinkedIn - Valentina Putri](https://linkedin.com/in/valentinaputri)  
📁 **Repository:** [GitHub - valentinaaptr](https://github.com/valentinaaptr)

