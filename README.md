### Link Folder Project berada pada repository berikut: <br>
https://github.com/triyanadewi/-05-website-pribadi-nextjs

---

# Laporan Praktikum Membuat Halaman yang SEO-Friendly dengan Next.js

|  | Pemrograman Berbasis Framework 2025 |
|--|--|
| NIM |  2241720206 |
| Nama |  Triyana Dewi Fatmawati |
| Kelas | TI - 3D |


## Langkah-langkah Praktikum
### 1. Memahami Pentingnya SEO
SEO (Search Engine Optimization) adalah praktik mengoptimalkan website agar mudah ditemukan oleh mesin pencari seperti Google. Dengan SEO yang baik, website Anda akan lebih mudah muncul di hasil 
pencarian, sehingga meningkatkan traffic pengunjung. <br>
Beberapa elemen penting dalam SEO: 
- Title Tag: Judul halaman yang muncul di hasil pencarian. 
- Meta Description: Deskripsi singkat tentang halaman. 
- Heading Tags (H1, H2, dll.): Struktur konten yang membantu mesin pencari memahami isi halaman. 
- URL Structure: URL yang deskriptif dan mudah dibaca. 
- Open Graph Tags: Metadata untuk media sosial seperti Facebook dan Twitter. 
- Favicon: Ikon kecil yang muncul di tab browser. 

---

### 2. Menambahkan Favicon 
Favicon adalah ikon kecil yang muncul di tab browser dan bookmark. Favicon membantu meningkatkan identitas brand website Anda. <br> 
**Langkah-langkah:**
1. Siapkan file favicon (format .ico) dan letakkan di folder public/.
2. Hapus faveicon.ico yang ada di folder src/app <br>
<img src="img/p2l2.png" alt="Favicon" width="100" height="auto">

3. Update file src/components/layout.tsx untuk menambahkan favicon: <br>
![Update File](img/p2l3.png)

4. Simpan dan jalankan proyek. Favicon akan muncul di tab browser. <br>
![Hasil Favicon](img/p2hasil.png)
---

### 3. Menambahkan Metadata untuk SEO 
Metadata seperti title dan description sangat penting untuk SEO. Metadata ini akan muncul di hasil pencarian dan membantu mesin pencari memahami konten halaman. <br>
**Langkah-langkah:** 
1. Buat file src/utils/metadata.ts untuk menyimpan metadata default: <br>
![Buat File Metadata](img/p3l1.png)

2. Update file src/components/layout.tsx untuk menggunakan metadata default jika tidak ada metadata yang di-pass: <br>
![Update File Layout](img/p3l2.png)

3. Update Setiap Halaman untuk dapat mem-pass definisi metadata, Halaman Tentang Saya: <br>
![Update Tentang Saya](img/p3l3.png)

4. Lanjutkan untuk halaman Proyek dan Esai <br>
Halaman Proyek: <br>
![Update Proyek](img/p3l4.png) <br>
Halaman Esai: <br>
![Update Esai](img/p3l5.png)
---

### 4. Open Graph Tags untuk Media Sosial 
Open Graph Tags digunakan untuk mengontrol bagaimana konten Anda ditampilkan saat dibagikan di media sosial seperti Facebook dan Twitter. <br>
**Langkah-langkah:** 
1. Pastikan Anda telah menambahkan Open Graph Tags di layout.tsx seperti yang telah dijelaskan sebelumnya. 
2. Update metadata di setiap halaman untuk menyertakan Open Graph Tags.

---

### 5. Menguji SEO 
Setelah menambahkan metadata, favicon, dan Open Graph Tags, Anda dapat menguji SEO dengan Membuka halaman di browser dan memeriksa elemen HTML menggunakan Developer Tools (Ctrl + Shift + I atau F12).
1. Halaman Tentang Saya <br>
![Tentang Saya](img/p5l1.png)

2. Halaman Proyek <br>
![Proyek](img/p5l2.png)

3. Halaman Esai <br>
![Esai](img/p5l3.png)

---

## Tugas 
Lakukan pengujian SEO dengan 
1. Gunakan tools seperti Google Search Console untuk memeriksa performa SEO dari suatu website. 

---

## Kesimpulan 
Dalam praktikum ini, Anda telah mempelajari cara membuat halaman Next.js yang SEO-friendly dengan menambahkan metadata, favicon, dan Open Graph Tags. Dengan teknik ini, website Anda akan lebih mudah ditemukan oleh mesin pencari dan menarik lebih banyak pengunjung. 