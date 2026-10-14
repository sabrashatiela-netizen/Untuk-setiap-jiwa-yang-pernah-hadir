# For Every Soul I've Met

Website surat umum untuk teman-teman, dibuat dengan HTML, CSS, dan JavaScript biasa. Bisa dijalankan secara lokal di VS Code dan diterbitkan gratis lewat GitHub Pages.

## Isi folder
- `index.html` — struktur halaman
- `style.css` — desain sage green dan cream, responsif
- `script.js` — 8 surat, kategori, surat acak, modal, salin surat, pesan kejutan, dan musik sintetis sederhana

## Menjalankan di VS Code
1. Ekstrak ZIP ini ke folder `for-every-soul`.
2. Buka VS Code → **File → Open Folder** → pilih folder tersebut.
3. Buka `index.html`.
4. Klik kanan pada area kode dan pilih **Open with Live Server** jika ekstensi Live Server sudah terpasang. Jika belum, kamu bisa membuka `index.html` langsung dari File Explorer dengan browser.

## Menerbitkan di GitHub Pages
1. Buat repository baru di GitHub. Contoh nama: `for-every-soul`. Pilih **Public**.
2. Buka repository → **Add file → Upload files**.
3. Unggah `index.html`, `style.css`, `script.js`, dan `README.md` dari folder ini ke root repository (jangan dimasukkan ke subfolder).
4. Klik **Commit changes**.
5. Buka **Settings → Pages**.
6. Pada **Build and deployment**, pilih **Deploy from a branch**.
7. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
8. Tunggu beberapa menit. Di halaman Pages, gunakan tombol **Visit site** setelah website terbit.

Alamatnya biasanya `https://USERNAME.github.io/NAMA-REPOSITORY/`.

## Catatan
- Musik latar adalah nada sintetis sederhana dari Web Audio API; tidak memerlukan file musik tambahan. Browser hanya mengaktifkannya setelah pengunjung menekan tombol musik.
- Google Fonts memerlukan koneksi internet; jika tidak tersedia, font cadangan tetap digunakan.
- Repository dan website Public dapat dilihat siapa saja. Jangan menaruh informasi pribadi atau rahasia.
