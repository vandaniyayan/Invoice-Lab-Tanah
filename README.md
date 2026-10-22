# Invoice & Kwitansi Lab Tanah FP Unud (versi offline)

Aplikasi web satu file untuk membuat invoice dan kwitansi analisis sampel
(tanah, pupuk, POC, air, tanaman) berdasarkan *Rincian Biaya Analisis Tanah 2022*.
Berjalan **tanpa internet** dan tanpa instalasi.

## Cara pakai di Windows 7

1. Unduh repo ini (tombol **Code → Download ZIP** di GitHub), lalu ekstrak.
2. Klik dua kali `index.html`, atau klik kanan → *Open with* → Google Chrome / Firefox.
3. Isi data pengirim, pilih tarif (A/B/C), jumlah sampel, dan jenis analisis.
4. Tekan **Cetak invoice**. Jika status **Lunas**, tombol **Cetak kwitansi** ikut muncul.
   Di jendela cetak bisa pilih printer atau *Save as PDF*.

## Browser yang didukung

| Browser | Versi terakhir untuk Windows 7 | Status |
|---|---|---|
| Google Chrome | 109 | Didukung |
| Mozilla Firefox ESR | 115 | Didukung |
| Internet Explorer | 11 | Tidak didukung |

## Catatan

- Data isian terakhir tersimpan otomatis di browser komputer tersebut (localStorage).
  Data tidak terkirim ke mana pun.
- Info virtual account hanya tampil jika opsi *Pembayaran via virtual account* dicentang.
- Kwitansi hanya muncul jika status pembayaran **Lunas**.
- Untuk mengubah tarif, edit daftar `ITEMS` di dalam `index.html` (kolom harga A, B, C).
