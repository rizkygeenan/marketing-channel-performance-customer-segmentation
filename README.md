# 📊 Marketing Channel Performance & Customer Segmentation Analysis

---

## 📌 Project Overview
Project ini bertujuan untuk menganalisis performa berbagai *marketing channel* (Email, Facebook, Google, Instagram, WhatsApp, YouTube) dalam mendatangkan **impressions**, **clicks**, dan **conversions**. Melalui proses *data understanding*, *preprocessing*, visualisasi interaktif pada Power BI, serta *customer segmentation*, analisis ini memberikan rekomendasi strategis berbasis data untuk mengoptimalkan alokasi anggaran pemasaran dan strategi peluncuran produk baru.

---

## 🎯 Business Objectives & Questions

### 1. Business Objectives
- Memahami struktur data performa *marketing channel* secara agregat dan periodik[cite: 3, 4].
- Membandingkan efektivitas antar *channel* menggunakan visualisasi *dashboard*[cite: 3].
- Mengidentifikasi efektivitas *channel* berdasarkan metrik utama (*Impressions, Clicks, Conversions, CTR, CVR, CPC, CPM, ROI, ROAS*)[cite: 3, 4].
- Melakukan segmentasi pelanggan untuk menentukan target audiens yang tepat berdasarkan *Avg. Revenue per Target Audience*[cite: 3, 7].
- Menghasilkan rekomendasi bisnis berbasis data (*data-driven recommendations*) untuk peluncuran produk baru[cite: 7, 8, 9].

### 2. Business Questions
1. **Brand Awareness & Sales**: *Channel* mana yang paling efektif untuk meningkatkan *brand awareness* dan mendongkrak penjualan[cite: 4, 5, 6]?
2. **New Product Launch**: Jika perusahaan meluncurkan produk baru berupa **tas perempuan seharga $100**, *channel* dan segmen audiens mana yang paling tepat untuk ditargetkan[cite: 7, 8]?

---

## 🛠️ Tools & Technologies Used
- **Google Colaboratory / Python**: Data Preprocessing & Exploratory Data Analysis (EDA).
- **Power BI**: Interactive Dashboard & Visualizations[cite: 3].
- **Google Docs / Slide / PDF**: Executive Summary & Presentation[cite: 1, 12].

---

## 📂 Dataset Overview
Dataset yang digunakan mencakup metrik performa kampanye pemasaran digital (periode Juli 2024 – April 2025) dengan ringkasan metrik agregat utama[cite: 3, 4]:

| Metrik Utama | Nilai Agregat | Deskripsi |
| :--- | :--- | :--- |
| **Total Impressions** | **3.06bn** | Total kemunculan iklan (*brand awareness*)[cite: 3, 4] |
| **Total Clicks** | **260M** | Total interaksi/klik pada iklan[cite: 3, 4] |
| **Total Conversions** | **57M** | Total transaksi/tindakan sukses yang dihasilkan[cite: 3, 4] |
| **CTR (Click-Through Rate)** | **8.51%** | Rata-rata rasio klik terhadap impresi[cite: 3, 4] |
| **CVR (Conversion Rate)** | **22.03%** | Rata-rata rasio konversi terhadap klik[cite: 3, 4] |
| **CPC / CPM** | **$0.079 / $6.707** | Efisiensi biaya per klik dan per seribu impresi[cite: 3] |
| **ROI / ROAS** | **35.11% / 1.40K** | Efisiensi dan pengembalian investasi iklan[cite: 3, 4] |

---

## 🔄 Data Preprocessing & Methodology

1. **Data Cleaning & Formatting**:
   - Memeriksa dan menangani nilai yang hilang (*missing values*) serta duplikasi data.
   - Memastikan tipe data tiap kolom sesuai (numerik untuk metrik, kategorikal untuk saluran/segmen).
2. **Feature Engineering / Calculated Metrics**:
   - Menghitung **CTR (%)** = `Clicks` / `Impressions` untuk mengukur daya tarik iklan[cite: 4].
   - Menghitung **Conversion Rate / CVR (%)** = `Conversions` / `Clicks` untuk mengukur efektivitas *channel* dalam menghasilkan penjualan[cite: 4].
   - Menghitung **ROAS** untuk mengukur profitabilitas finansial tiap *channel*[cite: 4, 6].
3. **Customer Segmentation**:
   - Menganalisis *Avg. Revenue per Target Audience* pada segmen: *Premium Shoppers, College Students, Tier 2 City Customers, Working Women, dan Youth*[cite: 3, 7].

---

## 📊 Key Findings & Insights

### 1. Performa Marketing Channel
- **Brand Awareness (*Impressions*)**: 
  - **YouTube** (**515.04M**) dan **Instagram** (**514.00M**) memimpin jangkauan terluas, terutama pada puncak periode Jul–Okt 2024 (~141M impresi)[cite: 4, 5].
- **Daya Tarik & Interaksi (*CTR*)**:
  - **Email Marketing** mencatatkan CTR tertinggi puncak sebesar **8.63%** pada Oktober 2024, menunjukkan relevansi pesan promosi yang sangat kuat[cite: 5].
- **Penjualan & Konversi (*Conversions & CVR*)**: 
  - **Instagram** menjadi pendorong konversi utama dengan jumlah konversi tertinggi (**9.75M**) dan CVR puncak mencapai **22.28%** pada Januari 2025[cite: 4, 6].
- **Profitabilitas Finansial (*ROAS*)**: 
  - **Email Marketing** menghasilkan efisiensi retensi dan pengembalian tertinggi dengan ROAS sebesar **1,422.28** (puncak **1,487.13** pada Oktober 2024)[cite: 4, 6].

---

### 2. Strategi Peluncuran Produk Baru (Tas Perempuan - $100)
- **Target Channels**:
  1. **Instagram** (*Awareness & Conversion Engine*): *Channel* utama untuk *visual showcase*, *influencer seeding*, dan transaksi langsung via *Shoppable Posts* (CVR 22.20%)[cite: 7, 8].
  2. **YouTube** (*Brand Awareness Booster*): Penghasil impresi terbesar (515.04M) yang ideal untuk konten *unboxing* dan *deep-review*[cite: 8].
  3. **Email Marketing** (*Profitability & Retargeting*): Pencetak ROAS tertinggi (1,422.28) untuk penawaran eksklusif dan *retargeting* pelanggan potensial/VIP[cite: 7, 8].
- **Target Segmen**:
  - **Primary Target**: **Working Women** (*Avg. Revenue*: $0.51M) — Memiliki kebutuhan terkuat terhadap tas $100 untuk menunjang penampilan dan aktivitas profesional, dengan daya beli stabil serta tingkat konversi berulang yang tinggi[cite: 7].
  - **Secondary Target**: **Premium Shoppers & College Students** (*Avg. Revenue*: $0.52M) — Segmen dengan ketertarikan tinggi pada tren gaya hidup & produk *branded* yang sangat responsif terhadap konten visual di Instagram & YouTube[cite: 7].

---

## 💡 Business Recommendations

1. **Alokasi Anggaran Utama**:
   - Fokuskan porsi bujet terbesar pada **Instagram** (untuk *visual branding* & konversi penjualan) dan **YouTube** (untuk perluasan *brand awareness* awal)[cite: 8, 9].
2. **Retargeting Berbasis Email**:
   - Gunakan strategi *retargeting* otomatis via Email bagi calon pembeli yang telah berinteraksi untuk memaksimalkan pengembalian investasi (ROAS puncak 1,487.13)[cite: 6, 9].
3. **Targeting Spesifik Segmen**:
   - Salurkan promosi produk tas $100 secara khusus kepada **Working Women** dan **Premium Shoppers** melalui *messaging* bernilai profesional dan eksklusif[cite: 7, 9].
4. **Optimalisasi Periode Kampanye**:
   - Manfaatkan pola lonjakan CVR pada Q4–Q1 (Januari menyentuh CVR **22.28%**) untuk mengoptimalkan momen belanja musiman[cite: 6, 9].

---

## 📈 Dashboard Preview
<img width="864" height="488" alt="marketing-channel-analytics-dashboard" src="https://github.com/user-attachments/assets/fe63ffd1-a36b-45c2-9472-95c0f4c87898" />


---

- ## 👤 Author

- **Nama**: Muhammad Rizky Ginanjar
- **Role**: Data Analyst
- **LinkedIn**: [Muhammad Rizky Ginanjar](https://www.linkedin.com/in/rizkyginan/)
