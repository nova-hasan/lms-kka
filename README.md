# lms-kka

Website pembelajaran statis untuk GitHub Pages. Tidak memerlukan hosting berbayar atau proses build.

## Fitur
- 6 topik pembelajaran awal: berpikir komputasional, algoritma/instruksi, pembersihan data, Scratch, pengenalan AI, etika digital.
- Filter topik.
- Ringkasan materi dalam jendela pop-up.
- Checklist progres yang tersimpan di browser perangkat murid.
- Kuis singkat dengan skor otomatis.
- Tampilan responsif untuk komputer dan ponsel.

## Cara menjalankan di komputer
1. Ekstrak ZIP.
2. Buka folder `lms-kka-kelas8`.
3. Klik dua kali `index.html`, atau buka dengan browser.

## Cara menerbitkan di GitHub Pages
1. Masuk ke https://github.com dan login/daftar.
2. Klik tombol **+** di kanan atas, lalu pilih **New repository**.
3. Isi nama repository, misalnya `lms-kka-kelas8`.
4. Pilih **Public**, lalu klik **Create repository**.
5. Pada halaman repository, klik **Add file** → **Upload files**.
6. Unggah `index.html` dari folder proyek ini (opsional: unggah juga `README.md`).
7. Klik **Commit changes**.
8. Buka tab **Settings** repository.
9. Pilih **Pages** pada menu samping.
10. Di bagian **Build and deployment**, pilih **Deploy from a branch**.
11. Pada **Branch**, pilih `main` dan folder `/(root)`, lalu klik **Save**.
12. Tunggu beberapa menit, lalu segarkan halaman Settings → Pages. Tautan website akan tampil di sana, biasanya berbentuk `https://NAMA-USER.github.io/lms-kka-kelas8/`.

## Cara memperbarui materi
Edit `index.html` di komputer, lalu unggah ulang ke repository dengan nama yang sama dan pilih commit perubahan. Bisa juga klik file `index.html` di GitHub, klik ikon pensil **Edit**, lalu commit perubahan.

## Batasan versi awal
- Progres disimpan di `localStorage` browser pada perangkat masing-masing; tidak tersinkron antarperangkat dan tidak terlihat oleh guru.
- Kuis berjalan di browser; skor belum dikirim ke guru.
- Belum ada login, kelas privat, database, atau pengumpulan tugas.
- Jangan menaruh data pribadi murid atau informasi rahasia dalam website publik.
- Jika membutuhkan nilai terpusat, akun murid, pengumpulan tugas, dan dashboard guru, perlu ditambahkan backend atau layanan LMS/formulir yang sesuai.

## Catatan isi
Materi ini adalah contoh awal. Guru perlu menyesuaikan isi, tujuan pembelajaran, dan asesmen dengan CP/ATP serta kebijakan sekolah.
