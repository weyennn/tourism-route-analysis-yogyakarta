# Analisis Rute Wisata Yogyakarta Berbasis Graf

## Latar Belakang Masalah
Perencanaan rute perjalanan wisata sering kali tidak mempertimbangkan
efisiensi jarak secara optimal, terutama ketika terdapat banyak destinasi
yang dapat dipilih. Tanpa bantuan sistem analitis, wisatawan berpotensi
menghabiskan waktu dan jarak tempuh yang tidak efisien.

Proyek ini bertujuan untuk membangun aplikasi berbasis data graf
yang dapat menentukan **rute tercepat antar destinasi wisata di Yogyakarta**
serta menyajikan hasilnya dalam bentuk visualisasi yang mudah dipahami.

---

## Pendekatan Analisis
- Destinasi wisata direpresentasikan sebagai **node** dalam graf
- Jarak antar destinasi direpresentasikan sebagai **edge berbobot**
- Penentuan rute tercepat dilakukan menggunakan algoritma jalur terpendek
- Hasil analisis divisualisasikan dalam bentuk:
  - Graf rute perjalanan
  - Timeline perjalanan yang terstruktur

Pendekatan ini memungkinkan pengguna memahami **alur keputusan rute**
secara transparan dan visual.

---

## Fitur Utama
- Pencarian rute tercepat antar dua destinasi wisata
- Visualisasi graf rute dengan penandaan jalur terpilih
- Timeline perjalanan vertikal untuk memudahkan interpretasi rute
- Visualisasi dihasilkan secara real-time
- Tampilan responsif untuk desktop dan mobile

---

## Insight Utama
- Representasi graf membantu memodelkan hubungan antar destinasi secara sistematis.
- Visualisasi rute memperjelas hasil analisis jalur terpendek.
- Pendekatan ini dapat digunakan sebagai dasar pengambilan keputusan
  dalam perencanaan perjalanan wisata yang lebih efisien.

---

## Potensi Pengembangan
- Integrasi peta interaktif (Leaflet.js / Google Maps)
- Penambahan estimasi waktu tempuh dan moda transportasi
- Analisis rute multi-destinasi (tour planning)
- Pengayaan data destinasi (kategori, popularitas, kepadatan)

---

## Teknologi yang Digunakan
- Python & Flask
- NetworkX (pemodelan graf & analisis rute)
- Matplotlib (visualisasi graf)
- Jinja2 (templating)
- Vercel (deployment)

---

## Demo Aplikasi
🔗 https://pka-app2.vercel.app/

---

## Struktur Proyek
```
.
├── app.py
├── wsgi.py
├── requirements.txt
├── vercel.json
├── templates/
│   ├── index.html
│   └── rute.html
└── static/

```
---
## Penulis
Yayang Matira | Mahasiswa Magister Ilmu Komputer | Universitas Gadjah Mada
