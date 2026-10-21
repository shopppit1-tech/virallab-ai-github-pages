# ViralLab AI — Generator Konten Viral

## Isi
- `index.html`: website statis HTML, CSS, dan JavaScript.
- Integrasi Gemini API dari browser.
- Generate ide, angle, hook, judul, naskah narasi, arahan visual, deskripsi, hashtag, dan CTA.
- Tombol salin per bagian dan salin semua.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Unggah `index.html` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
6. Buka URL GitHub Pages yang muncul.

## Menggunakan Gemini API
1. Dapatkan API key dari Google AI Studio: https://aistudio.google.com/app/apikey
2. Buka situs yang sudah dipublikasikan.
3. Tempel API key pada kolom Gemini API Key, isi topik, lalu klik Generate.

## Peringatan keamanan
Versi ini memanggil Gemini API langsung dari browser. API key dapat dilihat oleh siapa pun yang memakai atau memeriksa situs. Karena itu:
- Jangan pasang key pribadi/berkuota besar pada situs publik.
- Gunakan hanya untuk uji coba/pribadi dengan pembatasan kuota.
- Untuk penggunaan publik atau dijual, pindahkan panggilan Gemini ke backend (misalnya Render/Cloud Functions) dan simpan key sebagai environment variable di server.
- Pantau kuota dan penggunaan API di Google AI Studio.
