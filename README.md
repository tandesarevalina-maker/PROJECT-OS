# PROJECT-OS
# tugas_so_saira
# LAPORAN PRATIKUM
## Nama: dwi indah revalina
## NIM: 05301425011
## MK : Sistem Operasi (project 1)
## Kelas : Sistem Informasi -A
## Script Membuat Struktur Direktori
### Script ini akan membuat folder baru dan mengisi setiap folder dengan file sama
https://drive.google.com/file/d/16ocsPXL599kYKI8XBaZseSU5ChS3U02V/view?usp=drivesdk
https://drive.google.com/file/d/1hQVcJZEKqK5-2lllwfYB0kQ1frZsJRai/view?usp=drivesdk

mkdir documents images archives logs
touch biru.txt merah.txt kuning.txt hijau.log hitam.csv / gambarsatu.jpg gambardua.png laporankeuangan.docx catatanhidup.md / arsipsatu.zip arsipdua.tar.gz dataone.json datatwo.json / script11.sh script22.sh catatanmati.txt error.log / fotokatanya.jpeg audiokatanya.mp3 testtest.txt
ls

## Script Mengorganisasi File
### Script ini akan mengorganisasi setiap file sesuai ekstensinya 
https://drive.google.com/file/d/1NG3LvMvNWHLD4Vkao6Xbei5NA4xDRnYb/view?usp=sharing

mv *.txt *.md documents/
mv *.jpg *.png *.jpeg images/
mv *.zip *.tar.gz archives/
mv *.log logs/
ls

## Fungsi Pencarian
### Saya telah menambahkan fitur pencarian agar mudah mencari file tertentu
https://drive.google.com/file/d/1VVQ9iuhpbMfx2iTJzGi0DcSj3w8t3-ZP/view?usp=sharing

find . -name "*.txt"
find . -size +1k
grep -R "ERROR" .

## Generet Laporan
### disini saya membuat script agar setiap perubahan pada file contohnya ukuran file, jumlah, dan tanggal di buat atau diubah. akan masuk pada file report.txt sebagai laporan

