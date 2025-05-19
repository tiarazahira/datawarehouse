# 📊 Analisis & Visualisasi Data **Layoffs**  
*Tugas Data Warehouse – Modul 06*

![Python](https://img.shields.io/badge/python-3.9%2B-blue?logo=python&logoColor=white) 
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) 
![Last Update](https://img.shields.io/badge/Last_Update-2025-05-19-orange)

Selamat datang di repositori proyek **Analisis & Visualisasi Data Layoffs**.  
Repo ini disiapkan sebagai deliverable **Tugas DW #6** dan berisi notebook, dataset, serta dokumentasi pendukung untuk memahami tren pemutusan hubungan kerja (_layoff_) global pada periode 2020‑2025.

---

## 🚀 Ringkasan Proyek
- **Notebook interaktif** (`layoffs_visualization.ipynb`) yang menggabungkan *data cleaning*, *EDA*, dan *visualisasi*.
- **Analisis kebutuhan** (Requirements Analysis) berdasarkan materi kuliah *slide* **“06 Requirements Analysis”**.
- Visualisasi berupa:
  1. Tren total PHK per bulan  
  2. 10 Industri dengan PHK terbanyak  
  3. 10 Negara dengan PHK terbanyak  
  4. Scatter *Tahap Pendanaan* vs *Total PHK*
- Ditulis sepenuhnya dalam **Bahasa Indonesia** agar mudah dipahami rekan satu kelas.

---

---

## ⚙️ Persyaratan Sistem
| Perangkat Lunak | Versi Minimum | Cara Instalasi |
|-----------------|---------------|----------------|
| Python | 3.9 | <code>sudo apt install python3</code> / installer resmi |
| pip | 22 | <code>python -m ensurepip --upgrade</code> |
| Jupyter Notebook/Lab | 6 / 3 | <code>pip install jupyter&nbsp;lab</code> |
| pandas | 1.5 | <code>pip install pandas</code> |
| matplotlib | 3.7 | <code>pip install matplotlib</code> |

> **Tip:** Gunakan *virtual environment* (`venv` atau `conda`) agar dependensi proyek terisolasi.

---

## 🔧 Cara Cepat Menjalankan
```bash
# 1. (Opsional) buat virtual env
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 2. Instal dependensi
pip install -r requirements.txt  # atau perintah pip install di tabel atas

# 3. Jalankan Jupyter
jupyter notebook
# Buka layoffs_visualization.ipynb lalu pilih Run ▶️ → Run All
```

---


## 📝 Penjelasan Notebook
1. **Analisis Kebutuhan** – merangkum lima pendekatan (data‑, goal‑, process‑, user‑, externally‑driven).  
2. **Data Cleaning** – parsing `date`, konversi tipe `Int32`, normalisasi persentase & dana terkumpul.  
3. **Visualisasi** – empat grafik utama + *insight* singkat.  
4. **Kesimpulan** – temuan awal & saran eksplorasi lanjutan.

---

## 💾 Sumber Data
Dataset berasal dari **Layoffs.fyi** ( https://www.kaggle.com/datasets/swaptr/layoffs-2022 ).  
Lisensi data mengikuti ketentuan situs sumber.

---

## 📚 Referensi
- Slide **“06 Requirements Analysis”**  
- Dokumen **“Tugas DW 06”**  
- [pandas Documentation](https://pandas.pydata.org/docs/)  
- [matplotlib Documentation](https://matplotlib.org/stable/index.html)

---



