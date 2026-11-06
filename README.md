# Portfolio Muhammad Mushleh

Website portfolio satu halaman yang dibuat menggunakan HTML, CSS, dan JavaScript biasa. Tidak membutuhkan framework atau proses instalasi.

## Cara membuka website

1. Ekstrak file ZIP.
2. Buka folder `mushleh-portfolio` menggunakan Visual Studio Code.
3. Buka file `index.html` di browser. Untuk pengalaman pengembangan yang lebih nyaman, gunakan ekstensi Live Server di VS Code.
4. Pastikan folder `assets` tetap berada satu tingkat dengan `index.html` agar foto dan CV dapat tampil/diunduh.

## Struktur folder

```text
mushleh-portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── profile-muhammad-mushleh.png
    └── CV_Muhammad_Mushleh.pdf
```

## Bagian yang bisa diedit

- `index.html`: nama, deskripsi, pendidikan, pengalaman, keahlian, nomor WhatsApp, dan email.
- `style.css`: warna, ukuran, jarak, dan tampilan responsif.
- `script.js`: menu navigasi, penanda menu aktif, dan animasi saat halaman digulir.
- `assets/`: foto profil dan file CV.

## Mengunggah ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `mushleh-portfolio`.
2. Unggah seluruh isi folder ini ke repository. Pastikan `index.html` berada di direktori utama repository.
3. Buka **Settings → Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu simpan.
6. Tunggu proses publikasi selesai. GitHub akan menampilkan alamat website pada halaman Pages.

Catatan: foto dan CV sudah disertakan di folder `assets`. Jangan memindahkan atau mengganti nama file tersebut tanpa menyesuaikan alamatnya di `index.html`.
