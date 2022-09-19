# Aplikasi Penghubung antara orang tua/wali murid dengan guru (SD)

## Permasalahan
- Sebagian orang tua kurang memperhatikan perkembangan anaknya di sekolah karena sibuk
- Surat pemberitahuan dari sekolah tidak sampai kepada orang tua karena hilang/rusak/disembunyikan siswa
- Siswa kurang mendengarkan/menangkap info yang disampaikan guru sehingga terjadi kesalahan informasi

## Rancangan solusi
- Bikin aplikasi yang bisa menghubungkan antara semua guru mata pelajaran dengan orang tua siswa supaya ortu bisa ngecek perkembangan anaknya kapan aja
- Di dalam aplikasinya harus ada jadwal pelajaran, daftar hadir, daftar nilai, halaman pengumuman, fitur chat dengan guru tiap mapel dan wali kelas, fitur catatan siswa

## Use Case
- User guru bisa memposting pengumuman di halaman pengumuman tentang PR, studytour, jadwal UTS, dll.
- User guru bisa menampilkan data siswa kepada orang tuanya
- User orang tua bisa melihat pengumuman di halaman pengumuman
- User orang tua bisa melihat data anaknya
- User orang tua bisa berdiskusi dengan guru melalui fitur chat
- User orang tua bisa menanggapi postingan guru

## Struktur Data

### Guru
Atribut|Tipe Data|Contoh
---|---|---
NIP|integer|19590416 198308 1 002
Nama|varchar|Diana
Kontak|varchar|08385541325

### Orang tua
Atribut|Tipe Data|Contoh
---|---|---
ID|integer|01123
Nama|varchar|Susi
Kontak|varchar|08381234178

### Siswa
Atribut|Tipe Data|Contoh
---|---|---
NISN|integer|00324514716
Nama|varchar|Febriani
Tempat Tanggal Lahir|varchar|Bandung, 17 Maret 2013
Jenis kelamin|string|Perempuan
Kelas|varchar|2B
No. Absen|integer|13


## UX Wireframe
![alt text](https://github.com/nurdilafarha/IF215007-IF215008/blob/main/Teori/UX%20Wireframe/Tak%20berjudul36_20220919075605.png)
