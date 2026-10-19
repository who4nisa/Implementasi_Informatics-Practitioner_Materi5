# Identitas Pembuat
* Nama: Anisa Julianti
* NPM: G1A023052
* Program Studi: Informatika, Universitas Bengkulu

---

# Studi Kasus Skripsi: Evaluasi Usability dan Redesign Dashboard Analitik UMKM Berbasis User-Centered Design

Repositori ini berisi implementasi kode program Python untuk analisis data pengujian kegunaan (usability testing) antarmuka dashboard analitik UMKM. Penelitian ini berfokus pada evaluasi perbandingan sebelum (Before Redesign) dan sesudah (After Redesign) perancangan ulang antarmuka menggunakan metode User-Centered Design (UCD) serta prinsip visualisasi data Shneiderman.

---

## 1. Latar Belakang dan Permasalahan
* Isu Industri: Banyak dashboard analitik laporan keuangan dan penjualan UMKM memiliki antarmuka yang rumit, tidak intuitif, serta menyulitkan pelaku usaha dalam mengambil keputusan bisnis secara cepat.
* Solusi Berbasis IT: Menerapkan perancangan ulang antarmuka berbasis User-Centered Design (UCD) untuk meningkatkan kenyamanan dan kemudahan pengguna.
* Tujuan Proyek (implementasi_materi5.py):
  1. Mensimulasikan data pengujian usability dari responden pelaku UMKM.
  2. Menganalisis metrik kuantitatif ganda meliputi System Usability Scale (SUS), Task Time (waktu penyelesaian tugas), dan Task Success Rate.
  3. Melakukan uji statistik inferensial (Paired t-test) untuk membuktikan signifikansi peningkatan kualitas antarmuka.
  4. Mengklasifikasikan grade rating usability standar industri dan mengekspor laporan komparatif ke format CSV.

---

## 2. Alur Kerja Analisis Data Usability
Skrip ini mengikuti tahapan evaluasi sistem interaktif standar:
1. Pembangkitan Data Responden: Mensimulasikan skor SUS, waktu pengerjaan, dan tingkat keberhasilan tugas dari 50 responden sebelum dan sesudah redesign.
2. Analisis Statistik Komparatif: Menghitung persentase peningkatan skor SUS, efisiensi waktu, serta tingkat keberhasilan tugas.
3. Uji Signifikansi Paired t-Test: Menguji apakah peningkatan skor SUS benar-benar signifikan secara statistik (p-value < 0.001).
4. Klasifikasi Grade SUS: Mengelompokkan skor SUS ke dalam standar grade industri (Grade A hingga Grade F).
5. Ekspor Laporan: Menyimpan hasil analisis lengkap ke dalam file laporan CSV.

---

## 3. Implementasi Kode (implementasi_materi5.py)

Skrip Python ini dibangun menggunakan pustaka standar analisis data dan statistik:

```python
# 1. Simulasi Data Responden dan Pengujian Usability Komprehensif
# 2. Analisis Statistik Komparatif dan Paired t-Test
# 3. Klasifikasi Grade Rating Usability Standar Industrial
# 4. Ekspor Laporan Lengkap ke Format CSV
# 5. Kesimpulan Akademis Penelitian HCI dan UCD
