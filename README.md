# Website Penjualan Gratis

Website toko fashion statis untuk GitHub Pages.

## Isi project

- `index.html` - halaman utama
- `produk.html` - katalog produk
- `keranjang.html` - keranjang belanja
- `checkout.html` - checkout
- `admin.html` - dashboard admin
- `style.css` - tampilan
- `app.js` - interaksi produk dan keranjang
- `images/` - folder gambar produk kamu sendiri

## Cara jalanin di lokal

1. Buka `index.html` langsung di browser.
2. Atau pakai Live Server di VS Code.

## Cara upload ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload semua file project ini ke repository.
3. Pastikan `index.html` ada di root folder.
4. Buka menu Settings > Pages.
5. Pilih sumber deployment dari branch `main` dan folder root, atau pakai workflow GitHub Actions di folder `.github/workflows`.

## Gambar produk sendiri

Taruh file gambar di folder `images/` lalu samakan nama file di `app.js`.

Contoh nama file yang dipakai:

- `images/boxy-tee-ivory.jpg`
- `images/boxy-tee-slate.jpg`
- `images/boxy-tee-sand.jpg`
- `images/boxy-tee-espresso.jpg`
- `images/relaxed-jeans-indigo.jpg`
- `images/straight-jeans-black.jpg`
