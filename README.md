# PA PBO Kel3
## Kelompok 3
#### Tita Nabila Putri (2209116092)
#### Kalengkongan John Derby (2209116061)

# Museum Karya Seni
Project ini membahas terkait manajemen Museum Karya Seni. Project ini mengusung pengembangan aplikasi manajemen museum karya seni dengan mengimplementasikan operasi CRUD (Create, Read, Update, Delete). 
Project ini akan membantu museum kami dalam melakukan pengelolaan data galeri seni, manajemen kelola staff informasi/konservasi, 
dan memberikan pengalaman yang menarik dan interaktif bagi para pengunjung. Project ini bertujuan untuk mengembangkan sistem manajemen museum karya seni yang efektif & efisien dalam galeri seni. 

## Flowchart
![DBD_Kel3 drawio](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/135780cf-e520-45f4-bed8-c63408111d97)

## ERD (Entity Relationship Diagram)
![Logical](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/d4204fbc-f8c4-4218-b642-ffa95573093c)

## Hierarki
![kel3 drawio](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/0cbc75f9-afeb-4d1f-82c8-804930977ad6)

## Screenshot Coding
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/d9dbdef2-fba0-4ef6-9f5a-5767780afa7d)
codingan di atas adalah metode CRUD dari ruang konservasi, setiap ruang memiliki masing-masing metode CRUD dan yang kami tampilkan adalah dari ruang konservasi.
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/94e2f73f-f6db-4473-9b38-8e4015709fe9)
codingan di atas adalah metode CRUD dari staff dengan mengeksekusi pernyataan SQL terhadap database dan menyimpan hasilnya dalam objek ResultSet (rs).
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/09bcdaf4-b0e9-4e13-9488-2eb0346620f0)
codingan di atas menggunakan metode setter getter untuk koneksi, dan terdapat metode main untuk memanggil setkoneksi untuk connect ke database saat program di-run.
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/18c41ceb-b7a1-4a94-9313-040d71af5bca)
Secara keseluruhan, setiap metode di atas bertanggung jawab untuk membuat objek suatu interface lalu memberikan tampilan interface tersebut kepada user ketika tombol ditekan.
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/89d5587b-19a9-411a-a1b6-6f211b960a49)
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/c77a5e7e-84c3-4370-a08e-2129006c223e)
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/f199b8e7-cab9-48b2-8554-7895a24c75b8)
dari keseluruhan codingan, tiga codingan di atas mengambil salah satunya saja. Untuk mode true, codingan memanggil metode edit pada objek pl yang mungkin merupakan objek untuk manajemen galeri seni dengan parameter yang sesuai kemudian menampilkan pesan dialog bahwa data berhasil diupdate. 
untuk mode false, codingan memanggil metode simpan pada objek pl dengan parameter yang sesuai kemudian menampilkan pesan dialog bahwa data berhasil disimpan.

## Output Program
pada saat program di-run akan tertampil pilihan-pilihan seperti gambar dibawah
![awal](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/881f4f4a-ea48-4b66-b699-7c12c5c3d0a8)
kemudian jika mengklik staff, maka akan tertampil menu CRUD bagian staff
![crud staf](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/5c26b674-6d18-4322-86d4-afc5eff60fa8)
sebelum mengisi, klik NEW yang terletak di kiri bawah, setelah itu baru bisa diisi
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/507b1359-3ade-40a7-becb-ad84b9ad8836)
tampilan jika berhasil disimpan :
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/a3f88cb3-305f-42f4-9275-55cc47bdde96)
jika ingin menghapus salahsatu kolom, cukup klik kolom lalu klik HAPUS
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/b1c6eea8-5460-4eb6-85be-92bdbbe0ac64)
berikut adalah tampilan create dari staff ruang informasi
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/0b461075-b0a9-48ac-9a55-b97bbf8dc2d9)
tampilan updatenya :
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/86aca282-2d11-4758-99ca-43233d1f7477)
tampilan delete :
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/5cdc5b97-a8b2-44a7-9ffa-2310a95f4ccc)
tampilan dari galeri_seni jika berhasil menyimpan
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/beb62c81-7492-416b-b1b5-06e2659122dc)
tampilan dari galeri ketika berhasil diupdate
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/95aa24ad-3b27-48c1-879e-506000f400ec)
 tampilan data pengunjung jika berhasil disimpan
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/0dec710f-2d7f-4bb5-ab8d-51f8cb54dd98)
tampilan ketika berhasil diupdate dan delete
![image](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/5dd7ad6e-ddef-4ccf-8fdc-a6e19188a6d1)
![p](https://github.com/titanabila/PA_PBO_Kel3/assets/126900340/928ae4f1-85fc-480b-a9bc-266849e43f6a)
