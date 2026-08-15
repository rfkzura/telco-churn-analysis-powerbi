# telco-churn-analysis-powerbi

# Customer Churn Analysis Dashboard

## Latar Belakang
Menganalisis data pelanggan telco untuk memahami pola churn 
(pelanggan berhenti berlangganan) dan faktor-faktor yang mempengaruhinya.

## Dataset
Sumber: [Telco Customer Churn - Kaggle]([link-kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data))
7,043 baris data pelanggan dengan 21 kolom (demografi, layanan, tagihan, status churn)

## Proses
1. Data cleaning di Power Query (perbaikan tipe data, handling nilai kosong, 
   standardisasi format kategori)
2. Membuat kolom Tenure Group untuk segmentasi
3. Membuat measure DAX (Churn Rate %, Total Customers, dll)
4. Membangun dashboard interaktif dengan slicer

## Key Insights
- Churn rate keseluruhan: 27%
- Pelanggan dengan kontrak Month-to-month churn jauh lebih tinggi 
  dibanding One year/Two year
- Pelanggan baru (tenure 0-12 bulan) paling rawan churn
- Pengguna Fiber optic churn lebih tinggi dibanding DSL
- Pembayaran via Electronic check punya churn rate tertinggi

## Tools
Power BI Desktop (Power Query, DAX, Data Visualization)

## Screenshot
![Dashboard](Screenshot-dashboard.png)
