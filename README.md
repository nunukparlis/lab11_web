# lab11_web

# 1. MEMBUAT DATABASE DAN MEMBUAT TABLE
![image](https://user-images.githubusercontent.com/81863210/122750099-4fd35f00-d2b8-11eb-9366-51675c0fc527.png)
# 2. MEMBUAT KONFIGURASI UNTUK MENGHUBUNGAKAN DENGAN DATABASE SERVER
![image](https://user-images.githubusercontent.com/81863210/122750536-d6883c00-d2b8-11eb-9a1f-bdbbd75f8509.png)
# 3. MEMBUAT MODEL UNTUK MEMPROSES DATA ARTIKEL . BUAT FILE BARU PADA DIREKTORI APP/MODELS DENGAN NAMA ARTIKELMODEL.PHP
![image](https://user-images.githubusercontent.com/81863210/122750904-4f879380-d2b9-11eb-97f4-79810e1e4a49.png)
# 4. BUAT CONTROLLER BARU DENGAN NAMA ARTIKEL.PHP PADA DIREKTORI APP/CONTROLLERS
![image](https://user-images.githubusercontent.com/81863210/122751303-ca50ae80-d2b9-11eb-8d63-f4a9fb5a8893.png)
# 5. Buat direktori baru dengan nama artikel pada direktori app/views, kemudian buat file baru dengan nama index.php
![image](https://user-images.githubusercontent.com/81863210/122751532-126fd100-d2ba-11eb-823e-2a2087cc914f.png)
# Mengakses URL http://localhost:8080/artikel
![image](https://user-images.githubusercontent.com/81863210/122752067-b35e8c00-d2ba-11eb-8917-42e5534f3ff2.png)
# 6. Tambahkan beberapa data pada database agar dapat ditampilkan datanya.
![image](https://user-images.githubusercontent.com/81863210/122753326-4fd55e00-d2bc-11eb-9f70-13bc2a9f76ae.png)
# Refresh URL http://localhost:8080/artikel
![image](https://user-images.githubusercontent.com/81863210/122754463-e8201280-d2bd-11eb-825f-77b6ef357518.png)
# 7. Tambahkan fungsi baru pada Controller Artikel
![image](https://user-images.githubusercontent.com/81863210/122754642-21588280-d2be-11eb-8af9-0262a0d941ca.png)
# 8. Buat view baru untuk halaman detail dengan nama app/views/artikel/detail.php
![image](https://user-images.githubusercontent.com/81863210/122754787-4baa4000-d2be-11eb-8716-8b4828f3e923.png)
# 9. Buka Kembali file app/config/Routes.php, kemudian tambahkan routing untuk artikel detail.
![image](https://user-images.githubusercontent.com/81863210/122755043-9d52ca80-d2be-11eb-9773-5da61fe8d108.png)
# Artikel 
![image](https://user-images.githubusercontent.com/81863210/122755298-fe7a9e00-d2be-11eb-9dd0-c0fd44574d0f.png)
# 10. Membuat Menu Admin
# Buat method baru pada Controller Artikel dengan nama admin_index()
![image](https://user-images.githubusercontent.com/81863210/122755740-a3957680-d2bf-11eb-950d-f1a789023e9d.png)
# 11. Selanjutnya buat view untuk tampilan admin dengan nama admin_index.php
![image](https://user-images.githubusercontent.com/81863210/122756313-75646680-d2c0-11eb-8a76-0b83b3ae4cc5.png)
![image](https://user-images.githubusercontent.com/81863210/122756390-8dd48100-d2c0-11eb-8a11-5b86a8895242.png)
# 12. Tambahkan routing untuk menu admin
![image](https://user-images.githubusercontent.com/81863210/122757109-7053e700-d2c1-11eb-8d43-ae9680dd47d6.png)
# 13. Akses menu admin dengan url http://localhost:8080/admin/artikel
![image](https://user-images.githubusercontent.com/81863210/122760531-6e8c2280-d2c5-11eb-9e56-6bb406dc0331.png)
# 14. Tambahkan fungsi/method baru pada Controller Artikel dengan nama add()
![image](https://user-images.githubusercontent.com/81863210/122761005-f1ad7880-d2c5-11eb-99a5-95b0582b955b.png)
# 15. Kemudian buat view untuk form tambah dengan nama form_add.php
![image](https://user-images.githubusercontent.com/81863210/122761315-4d780180-d2c6-11eb-9ff3-5d6fc639de91.png)
# 16. Akses menu tambah artikel dengan url http://localhost:8080/admin/artikel/add
![image](https://user-images.githubusercontent.com/81863210/122761505-84e6ae00-d2c6-11eb-821d-bff88e61ceae.png)
# 17. Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit()
![image](https://user-images.githubusercontent.com/81863210/122761965-09d1c780-d2c7-11eb-9d56-cc02b340900c.png)
# 18. Kemudian buat view untuk form tambah dengan nama form_edit.php
![image](https://user-images.githubusercontent.com/81863210/122762257-53221700-d2c7-11eb-848d-533538bc00d7.png)
# tampilan form edit
![image](https://user-images.githubusercontent.com/81863210/122762532-9d0afd00-d2c7-11eb-91b8-ed68fb9174d0.png)
# 19. Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete().
![image](https://user-images.githubusercontent.com/81863210/122762912-fecb6700-d2c7-11eb-9bc7-4d41fb21342a.png)
# Menambahkan Artikel
![image](https://user-images.githubusercontent.com/81863210/122763283-5964c300-d2c8-11eb-9648-c270a40d075f.png)
# tampilan setelah menambahkan Artikel
![image](https://user-images.githubusercontent.com/81863210/122763375-739ea100-d2c8-11eb-9158-5c26eb6726ff.png)
# tampilan sebelum menghapus artikel
![image](https://user-images.githubusercontent.com/81863210/122763592-b3658880-d2c8-11eb-8cce-2964fb6a4582.png)
# tampilan setelah menghapus artikel
![image](https://user-images.githubusercontent.com/81863210/122763666-ce37fd00-d2c8-11eb-996c-79d73213423e.png)
# tampilan sebelum mengedit
![image](https://user-images.githubusercontent.com/81863210/122763929-19521000-d2c9-11eb-9b6c-403182e67c6a.png)
# tampilan setelah mengedit
![image](https://user-images.githubusercontent.com/81863210/122764010-34248480-d2c9-11eb-9bbf-80e5930e0878.png)












