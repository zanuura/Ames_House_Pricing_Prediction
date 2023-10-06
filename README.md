# Ames_House_Pricing_Prediction

Real estate di Indonesia adalah industri properti yang mencakup berbagai jenis properti seperti rumah, apartemen, tanah, komersial, perumahan, dan properti industri.
Perkembangan real estate di Indonesia di pengaruhi oleh berbagai faktor diantaranya:
-Pertumbuhan Ekonomi
-Urbanisasi
-Kebijakan Pemerintah
-Pasar Properti Komersial
-Pembangunan Infrastruktur
dll
Perkembangan real estate di Indonesia di pengaruhi oleh berbagai faktor diantaranya: -Pertumbuhan Ekonomi -Urbanisasi -Kebijakan Pemerintah -Pasar Properti Komersial -Pembangunan Infrastruktur dll

## Seberapa penting sebuah sistem yang mampus menentukan harga rumah?

Pentingnya sistem yang mampu menentukan harga rumah tergantung pada berbagai faktor seperti:
- Pemilihan Properti untuk pembeli
- Penentuan Harga Jual untuk penjual
- Pengembangan Properti untuk developer
- Investasi Properti untuk investor

kemampuan untuk menentukan harga rumah dengan akurat dapat memiliki dampak besar pada keputusan dan transaksi properti.
Artificial Intelligence diharapkan dapat mendukung sistem tersebut untuk menghasilkan rekomendasi yang baik dan akurat

### Dataset Info

RangeIndex: 1460 entries, 0 to 1459 Data columns (total 81 columns):
- Id
- MSSubClass
- MSZoning
- LotFrontage
- LotArea
- ..........
- MoSold
- YrSold
- SaleType
- SaleCondition
- SalePrice
dtypes: float64(3), int64(35), object(43)

## Data Modeling

### Linear Regression
evaluation: 
- Mean Absolute Error: 4.689454779681475e+16 
- Mean Squared Error: 1.5268715044279774e+35 
- R-squared scores: 0,70

### Random Forest Regressor
evaluation: 
- Mean Absolute Error:  17357.92
- Mean Squared Error:   943047692.15 
- R-squared scores:  0.86

### XGBoost Regressor
evaluation: 
- Mean Absolute Error:  17588.08 
- Mean Squared Error:  875453541.77 
- R-squared scores:  0.87

### Features Imortance
OverallQual is the most feature importance
![image](https://github.com/zanuura/Ames_House_Pricing_Prediction/assets/73764446/8e88aa2c-5c9d-41d6-afbf-df98f5177316)

![image](https://github.com/zanuura/Ames_House_Pricing_Prediction/assets/73764446/b044c213-3033-4aa5-b417-adf68ce6f4a6)

#### OverallQual vs SalePrice
![image](https://github.com/zanuura/Ames_House_Pricing_Prediction/assets/73764446/d7278467-0a4c-45d0-8598-81e3813d3226)

## Modeling With Top 10 Features
### Linear Regression
evaluation: 
- Mean Absolute Error: 23482.96 
- Mean Squared Error: 2025148129.29 
- R-squared scores: 0.7

### Random Forest Regressor
evaluation: 
- Mean Absolute Error: 18754.26 
- Mean Squared Error: 989850716.99 
- R-squared scores: 0.85




