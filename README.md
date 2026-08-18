# Undian Lomba Video Konten

## Spreadsheet
Kolom:
1. Nama Peserta/Grup
2. Tema Lomba
3. Link video

Baris pertama adalah header. Data peserta dimulai dari baris 2.

## Google Apps Script
1. Buat project Apps Script.
2. Tempel isi `Code.gs`.
3. Ganti `SPREADSHEET_ID` dan `SHEET_NAME`.
4. Deploy sebagai Web App.
5. Set Execute as: Me.
6. Set Who has access: Anyone.
7. Salin URL `/exec`.

## Base64 URL
Di browser Console atau halaman kosong jalankan:

`btoa("URL_WEB_APP_ANDA")`

Salin hasilnya ke:

`const GAS_URL_B64 = "HASIL_BASE64";`

## GitHub Pages
Upload `index.html` ke repository GitHub dan aktifkan GitHub Pages.

Fitur:
- LIVE indicator
- Sinkronisasi otomatis setiap 15 detik
- Data peserta dari baris 2 sampai bawah
- PLAY/STOP undian
- Reveal nomor + nama + tema
- PLAY VIDEO UTUH
- Mendukung URL YouTube dan video direct (.mp4/.webm, dll.)
