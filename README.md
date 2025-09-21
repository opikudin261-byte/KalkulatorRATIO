# Kalkulator Redaman Fiber Optik

Aplikasi berbasis web untuk menghitung redaman (attenuation) pada jaringan fiber optik. Kalkulator ini memudahkan teknisi atau profesional jaringan dalam memperkirakan daya optik yang hilang akibat panjang kabel, konektor, splitter ratio, dan PLC splitter.

## 📌 Fitur Utama
- **Input Parameter**:
  - Daya sumber (OLT) dalam dBm
  - Jarak kabel (meter)
  - Ratio splitter (pembagian sinyal)
  - PLC splitter (pembagi sinyal pasif)
- **Hasil Kalkulasi**:
  - Daya sebelum splitter
  - Output setelah ratio splitter (Port 1 & Port 2)
  - Output akhir setelah PLC splitter
- **Interaktif & Modern**:
  - Tampilan responsif dengan **TailwindCSS**
  - Efek animasi saat hasil muncul
  - Fitur **copy to clipboard** untuk nilai daya optik
  - Tooltip informasi asumsi redaman standar

## 🛠️ Teknologi yang Digunakan
- **HTML5** untuk struktur halaman  
- **TailwindCSS** untuk styling dan tampilan responsif  
- **JavaScript** murni untuk kalkulasi & interaktivitas  
- **Google Fonts (Inter)** untuk tipografi modern  

## ⚙️ Asumsi Perhitungan
- Redaman kabel: **0.22 dB/km** (standar ITU-T G.652.D @ 1550 nm)
- Redaman konektor: **0.5 dB** (total untuk 2 konektor)

## 🚀 Cara Menggunakan
1. Unduh atau salin kode HTML ke file bernama `index.html`
2. Buka file tersebut di browser modern (Chrome, Firefox, Edge)
3. Masukkan parameter:
   - Daya sumber OLT (dBm)
   - Jarak kabel (meter)
   - Pilih ratio splitter & PLC splitter sesuai konfigurasi jaringan
4. Hasil kalkulasi akan muncul otomatis di sebelah kanan

## 📂 Struktur File
