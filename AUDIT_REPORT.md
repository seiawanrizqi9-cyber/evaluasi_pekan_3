1. Analisis Struktur Aset:
Gambar tidak berada pada folder images
file css tidak berada di folder css
file html tidak berada di folder html
file bat dan sh tidak masuk ke folder scripts
file log tidak masuk ke folder sripts

2. Perburuan bug visual:
css tidak berfungsi karena di index.html tertulis "href=style.sss"

3a. commit spesifik di mana file debug.log pertama kali ditambahkan: 
commit 0d965c4cf6ec50d591d60fe937600492726e4c9f
Author: iqbaljlldn <iqbaljalaludin1309@gmail.com>
Date:   Thu Aug 21 18:17:26 2025 +0700

    first commit
diff --git a/24-7-support.png b/24-7-support.png
new file mode 100644
index 0000000..e69de29
diff --git a/404.html b/404.html
new file mode 100644
index 0000000..e69de29
diff --git a/API.md b/API.md
new file mode 100644
index 0000000..e69de29

3b. identifikasi baris pasti yang mengandung informasi sensitif (API Key):
DEBUG: Auth details - User: admin, Key: xA-tOpSecReT-12345
