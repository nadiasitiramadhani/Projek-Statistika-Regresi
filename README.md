# 📊 Proyek Statistika Komputasi

Proyek ini merupakan implementasi **Statistika Komputasi menggunakan Python** yang berfokus pada analisis hubungan antarvariabel melalui regresi linear sederhana serta pengujian distribusi data.

Proyek mencakup proses analisis data, visualisasi, pengujian statistik, interpretasi hasil, dan penarikan kesimpulan berdasarkan hasil pengujian.

## 📌 Tujuan

Tujuan dari proyek ini adalah:

- Menganalisis hubungan antara variabel X dan Y menggunakan regresi linear sederhana.
- Menguji signifikansi hubungan linear antara X dan Y.
- Mengukur kemampuan variabel X dalam menjelaskan variasi variabel Y menggunakan koefisien determinasi (R²).
- Menguji distribusi data X dan Y menggunakan beberapa metode statistik.
- Membandingkan hasil pengujian statistik dengan visualisasi data.

## 🔬 Analisis yang Dilakukan

### 1. Regresi Linear Sederhana

Regresi linear digunakan untuk mengetahui hubungan antara variabel independen (X) dan variabel dependen (Y), sekaligus memprediksi nilai Y berdasarkan X.

Model regresi yang digunakan:

**Ŷ = a + bX**

Analisis meliputi:

- Persamaan regresi linear
- Koefisien slope dan intercept
- Uji signifikansi
- t-statistik
- F-statistik
- p-value
- Koefisien determinasi (R²)
- Interpretasi hasil regresi

Hasil analisis menunjukkan persamaan regresi:

**Ŷ = 53.8666 − 0.0741X**

Dengan p-value sebesar **0.4233** dan R² sebesar **0.0006**. Karena p-value > 0.05, hubungan linear antara X dan Y tidak signifikan. Nilai R² menunjukkan bahwa hanya sekitar **0.06% variasi Y** yang dapat dijelaskan oleh X.

## 📈 2. Pengujian Distribusi

Distribusi data X dan Y diuji menggunakan beberapa metode:

- Kolmogorov-Smirnov
- Anderson-Darling
- Shapiro-Wilk
- Chi-Square

Pengujian dilakukan untuk mengetahui apakah data memenuhi asumsi distribusi normal.

### Hasil Pengujian

| Metode | Data X | Data Y |
|---|---|---|
| Shapiro-Wilk | Normal | Tidak Normal |
| Chi-Square | Normal | Tidak Normal |
| Kolmogorov-Smirnov | Normal | Tidak Normal |
| Anderson-Darling | Normal | Tidak Normal |

Hasil pengujian menunjukkan bahwa **data X dapat dianggap berdistribusi normal**, sedangkan **data Y tidak berdistribusi normal**.

## 📊 3. Visualisasi

Visualisasi digunakan untuk mendukung interpretasi hasil analisis statistik.

Visualisasi yang digunakan antara lain:

- Histogram
- Density Plot
- Q-Q Plot
- Boxplot
- Visualisasi regresi
- Residual Plot

Hasil visualisasi mendukung kesimpulan dari pengujian statistik terhadap distribusi X dan Y.

## 🛠️ Tools & Library

Proyek ini dibuat menggunakan:

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **SciPy**
- **Statsmodels**

## 📂 Struktur Repository

```text
projek-statistika-komputasi/
│
├── PROJEK EAS STATKOM NADIA.html
└── README.md
```

File HTML merupakan hasil export dari notebook yang berisi kode, proses analisis, visualisasi, hasil pengujian, dan kesimpulan proyek.

## 📋 Kesimpulan

Berdasarkan keseluruhan analisis, data X memenuhi asumsi normalitas berdasarkan beberapa metode pengujian, sedangkan data Y tidak memenuhi asumsi normalitas. Hasil regresi linear juga menunjukkan bahwa variabel X tidak memiliki pengaruh linear yang signifikan terhadap variabel Y.

Proyek ini menunjukkan penerapan konsep **statistika komputasi menggunakan Python**, mulai dari analisis regresi, pengujian hipotesis, pengujian distribusi, hingga visualisasi dan interpretasi hasil.

## 👩‍💻 Author

**Nadia Siti Ramadhani**

Mahasiswa Sains Data  
UPN "Veteran" Jawa Timur
