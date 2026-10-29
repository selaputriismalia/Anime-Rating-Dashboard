# Anime Rating Dashboard

Dashboard interaktif berbasis **Streamlit** untuk mengeksplorasi dan memahami data rating anime. Proyek ini dipisahkan dari repository **CRISP-DM Anime Rating Analysis** agar aplikasi dashboard dan proses analisis data dapat ditampilkan sebagai dua proyek portofolio yang berbeda.

## Tujuan Proyek

Menyajikan informasi dari dataset anime dalam bentuk visualisasi yang lebih mudah dipahami, sehingga pengguna dapat melihat gambaran umum data rating anime dan pola-pola yang muncul.

## Fitur Dashboard

- **Data Overview** — menampilkan ringkasan dan pratinjau dataset.
- **Rating Distribution** — melihat distribusi rating anime.
- **Genre Analysis** — mengeksplorasi genre yang tersedia pada dataset.
- **Anime Type Analysis** — membandingkan kategori tipe anime, seperti TV atau Movie, jika tersedia pada dataset.
- **Clustering Visualization** — menampilkan hasil pengelompokan data anime untuk membantu eksplorasi pola.
- **Rating Insights** — menampilkan anime dengan nilai rating tertinggi dan terendah berdasarkan data yang digunakan.

> Fitur yang tampil bergantung pada versi aplikasi dan kolom dataset yang tersedia. Dashboard ini berfokus pada eksplorasi dan visualisasi data; hasil clustering bukan rekomendasi personal untuk pengguna.

## Teknologi

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Menjalankan Secara Lokal

1. Clone repository ini:

   ```bash
   git clone https://github.com/selaputriismalia/Anime-Rating-Dashboard.git
   cd Anime-Rating-Dashboard
   ```

2. Buat dan aktifkan virtual environment (opsional tetapi disarankan):

   ```bash
   python -m venv .venv
   ```

   Windows:

   ```bash
   .venv\Scripts\activate
   ```

   macOS/Linux:

   ```bash
   source .venv/bin/activate
   ```

3. Install dependensi setelah file `requirements.txt` tersedia:

   ```bash
   pip install -r requirements.txt
   ```

4. Jalankan aplikasi Streamlit setelah source aplikasi dan dataset ditambahkan:

   ```bash
   streamlit run main.py
   ```

## Struktur Proyek

Struktur berikut merupakan struktur yang dituju; nama file dapat disesuaikan dengan source code aplikasi yang dipulihkan.

```text
Anime-Rating-Dashboard/
├── main.py
├── requirements.txt
├── data/
│   └── anime.csv
└── README.md
```

## Catatan

Repository ini disiapkan khusus untuk proyek dashboard. Source code aplikasi dan dataset perlu ditambahkan atau dipulihkan sebelum aplikasi dapat dijalankan. Pastikan penggunaan dataset mengikuti ketentuan lisensi dan atribusi dari sumbernya.

## Proyek Terkait

- [CRISP-DM Anime Rating Analysis](https://github.com/selaputriismalia/CRISP-DM-Deployment-Anime-Rating-Analysis) — repository terpisah untuk dokumentasi proses analisis data.
