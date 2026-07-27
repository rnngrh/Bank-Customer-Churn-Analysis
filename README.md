# Bank-Customer-Churn-Analysis

Analisis data pelanggan bank untuk memahami faktor-faktor yang memengaruhi Customer Churn (pelanggan berhenti menggunakan layanan bank). Proyek ini mencakup proses Data Understanding, Data Cleaning, Exploratory Data Analysis (EDA), serta penyusunan insight dan rekomendasi bisnis berbasis data.

## Tujuan Project

- Memahami karakteristik pelanggan bank.
- Mengidentifikasi faktor yang memengaruhi Customer Churn.

## Dataset

Dataset yang digunakan berasal dari Kaggle:

**Bank Customer Churn Prediction Dataset**

Dataset berisi informasi mengenai pelanggan bank, seperti:

- Customer ID
- Credit Score
- Country
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Active Member
- Estimated Salary
- Churn Status


## 🔍 Tahapan Analisis

### 1. Data Understanding

Tahap awal dilakukan untuk memahami struktur dataset, tipe data, jumlah data, serta distribusi setiap variabel.

### 2. Data Cleaning

Proses pembersihan data meliputi:

- Pemeriksaan missing values
- Pemeriksaan duplicate data
- Pemeriksaan tipe data

### 3. Exploratory Data Analysis (EDA)

Analisis dilakukan untuk menjawab beberapa pertanyaan bisnis, seperti:

- Bagaimana distribusi Customer Churn?
- Apakah negara pelanggan memengaruhi churn?
- Apakah gender memengaruhi churn?
- Apakah usia memengaruhi churn?
- Apakah jumlah produk memengaruhi churn?
- Apakah status pelanggan aktif memengaruhi churn?
- Apakah Credit Score memengaruhi churn?
- Apakah Estimasi Gaji Berpengaruh terhadap Customer Churn?


## Insight yang Dihasilkan

Beberapa insight yang diperoleh antara lain:

- Sekitar 80% pelanggan masih bertahan, sedangkan sekitar 20% pelanggan telah berhenti menggunakan layanan bank (churn). Hal ini menunjukkan bahwa tingkat churn masih cukup tinggi karena satu dari lima pelanggan memutuskan untuk meninggalkan layanan bank.
- Pelanggan dari Germany memiliki persentase customer churn paling tinggi dibandingkan negara lainnya. Hal ini mengindikasikan adanya kemungkinan faktor tertentu di negara tersebut yang memengaruhi keputusan pelanggan untuk berhenti menggunakan layanan bank.
- Pelanggan perempuan pada dataset ini memiliki kecenderungan lebih tinggi untuk berhenti menggunakan layanan bank dibandingkan pelanggan laki-laki. Perbedaan ini mengindikasikan bahwa terdapat faktor lain yang mungkin memengaruhi keputusan pelanggan perempuan untuk melakukan churn. Pelanggan perempuan memiliki tingkat churn lebih tinggi pada dataset ini. Analisis lanjutan diperlukan untuk mengetahui faktor penyebabnya.
- Pelanggan yang tetap menggunakan layanan bank memiliki rata-rata usia 37,41 tahun, sedangkan pelanggan yang melakukan customer churn memiliki rata-rata usia 44,84 tahun.
- Hasil analisis menunjukkan bahwa jumlah produk yang dimiliki pelanggan memiliki hubungan yang cukup kuat dengan customer churn. Pelanggan yang hanya memiliki 1 produk memiliki tingkat churn sebesar 27,71%. Pelanggan dengan 2 produk memiliki tingkat churn paling rendah, yaitu 7,58%, yang menunjukkan tingkat loyalitas lebih tinggi. Sebaliknya, pelanggan yang memiliki 3 produk memiliki tingkat churn sangat tinggi, yaitu 82,71%. Seluruh pelanggan yang memiliki 4 produk pada dataset ini melakukan churn (100%). Namun, jumlah pelanggan pada kategori ini kemungkinan sangat sedikit.
- Pelanggan yang tidak aktif memiliki tingkat customer churn sebesar 26,85%, sedangkan pelanggan yang aktif memiliki tingkat churn yang lebih rendah yaitu 14,27%. Perbedaan ini menunjukkan bahwa pelanggan yang aktif menggunakan layanan bank cenderung lebih loyal dibandingkan pelanggan yang tidak aktif. Aktivitas pelanggan dapat menjadi salah satu indikator penting dalam mengidentifikasi risiko customer churn.
- Rata-rata credit score pelanggan yang tetap menggunakan layanan bank adalah 651,85, sedangkan pelanggan yang melakukan churn memiliki rata-rata 645,35. Perbedaan rata-rata tersebut relatif kecil, sehingga credit score belum menunjukkan hubungan yang kuat terhadap customer churn pada dataset ini.
- Rata-rata estimasi gaji pelanggan yang tetap menggunakan layanan bank adalah 99.738, sedangkan pelanggan yang melakukan churn memiliki rata-rata 101.466. Perbedaan tersebut relatif kecil sehingga estimasi gaji belum menunjukkan hubungan yang signifikan dengan customer churn.

## Teknologi yang Digunakan

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- KaggleHub


## Tujuan Pembuatan

Project ini dibuat sebagai:

- Project Mandiri Portfolio Data Analyst
- Latihan Exploratory Data Analysis (EDA)
- Implementasi analisis data menggunakan Python


## Author

**Rian Nugraha**
