# Konsep-Synchronous-Asynchronous

1. Penjelasan Synchronous

Synchronous (sinkron) adalah pola eksekusi kode secara berurutan (sequential) dari atas ke bawah.
Dalam pola ini, setiap tugas harus menunggu tugas sebelumnya selesai sebelum bisa dijalankan.
Jika ada proses yang membutuhkan waktu lama (misalnya mengambil data dari server atau membaca file besar), baris kode berikutnya akan terblokir (blocking) sampai proses tersebut selesai.

2. Penjelasan Asynchronous

Asynchronous (asinkron) adalah pola eksekusi kode di mana tugas-tugas dapat berjalan tanpa harus saling menunggu (non-blocking).
Dalam pola ini, jika ada proses yang membutuhkan waktu lama, JavaScript tidak akan menghentikan seluruh program.
Proses lama tersebut akan dijalankan di latar belakang (background), sementara program langsung melanjutkan eksekusi ke baris kode berikutnya.
Setelah proses di latar belakang selesai, hasilnya akan diproses melalui mekanisme tertentu.

3. Perbedaan Synchronous dan Asynchronous
- Synchronous: Berurutan, Blocking = menahan eksekusi kode berikutnya., Total waktu = jumlah seluruh durasi tugas, dan Operasi sederhana, perhitungan logika dasar.
- Asynchronous: Dapat berjalan bersamaan seperti paralel, Non-blocking = kode berikutnya langsung dieksekusi, Lebih efisien karena proses berat dapat berjalan di latar belakang dan Request HTTP/API, membaca file, database query, timer.
