# Geting Started (Set Up Repository)
Panduan Kolaborasi Github 
Ini hanyalah salah satu dari banyak cara untuk berkolaborasi dalam sebuah proyek menggunakan GitHub. Ini merupakan cara yang paling mudah di fahabi bagi pemulai yang ingin berkolaborasi dalam suatu project dengan menambahkan kontributor baru.

## Langkah 1: Inisialisasi Proyek Baru
1. Buka Github dan klik tombol '+' di pojok kanan atas dan pilih 'New Repository'.

![buat repository 1](https://user-images.githubusercontent.com/111034379/184881870-fd7b6933-358b-456c-a05e-16629dfd57e3.png)

2. Kemudian isi kolom Repository name dan Description. buat sebagai public agar bisa di akses oleh user lain, dan untuk README nya biarkan saja tidak usah di ceklist. lalu Klik "Buat repositori".

![buat repository 2](https://user-images.githubusercontent.com/111034379/184882055-a90a98f6-b0d9-4960-8d78-572680134bac.png)

![step 2](https://user-images.githubusercontent.com/111034379/184882069-4b7771d3-add9-4c00-a090-a8c09f89cbae.png)

3. Lalu akan tampil halaman seperti berikut.

![step 3](https://user-images.githubusercontent.com/111034379/184882399-deb8ab42-86f5-47dd-84d7-c524a2d796d0.png)

3. Buat directory di komputer lokal Anda, buka folder tersebut lalu klik kanan dan open with gitbash .lalu ikuti intruksi script di repo lokal anda (seperti pada gambar di atas) Tempelkan baris kode secara berurutan dimulai dari "echo..." ke terminal / gitbash saat . Terminal Anda akan terlihat seperti berikut setelah Anda selesai:

![step 4](https://user-images.githubusercontent.com/111034379/184882464-a0a91665-6119-41a1-89c9-67603e8b4f19.png)

4. Coba kita buat sebuah file html sederhana, disini saya menggunakan VSCode kamu bisa menggunakan code editor lain. klik kanan pada folder repo lokal yang telah kita buat tadi lalu open with VSCode. Seperti pada gambar di bawah ini.

![step  7](https://user-images.githubusercontent.com/111034379/184880955-c8ad3fe2-7e8c-4e63-8e4b-2dd008588c36.png)

5. Lalu kita push ke remote (Repo Github)

![step 8 a](https://user-images.githubusercontent.com/111034379/184881156-74b633c4-9bdd-47c1-8d79-7ce2b2eef361.png)

6. Coba kita cek pada halaman githab nya, refresh browsernya. maka tampilannya akan seperti berikut. repo yang ada di lokal dan remote kita sudah up-to-date / sama.

![step 8](https://user-images.githubusercontent.com/111034379/184883067-f75ab984-b904-4c1c-bc3c-f859707879b7.png)

7. SELAMAT ANDA SUDAH BERHASIL MEMBUAT REPOSITORY DI GITHUB & MELAKUKAN REMOTE, SELESAI. 

# Langkah 2: SIAPKAN TIM (Tambahkan Kontributor)

Disini kamu sebagai User pertama yang akan menambahkan Contributor atau Tim baru, jadi Anda perlu menambahkan tim ke repo agar mereka dapat berkolaborasi. Setelah tim ditambahkan sebagai kolaborator, mereka akan dapat melakukan push, merge, and dan banyak hal lainnya (sederhananya tim kamu dapat melakukan edit atau menambahkan file projek baru ke repository milik-Mu), jadi pastikan ya Kamu hanya menambahkan rekan satu tim.

Oke kita coba!!! 

1. Klik pada tab “Settings” perwakilan Anda, lalu “Collaborators” lalu cari pengguna Github dan tambahkan mereka dengan mengklik "“Add Collaborator”":

![1](https://user-images.githubusercontent.com/111034379/184884978-57a025ab-559e-44f4-8eb2-3bb6595ac5e6.png)

![2](https://user-images.githubusercontent.com/111034379/184885207-a552cb84-e5c6-45ee-8d54-1fc316aba076.png)

2. Mereka akan menerima email yang memberitahukan bahwa Kamu menambahkan mereka dan akan terdaftar sebagai kolaborator. dalam posisi ini kamu adalah kolaborator yang di undang, kamu bisa klik pada bagian profile lalu kik "Your Organization" lalu kamu bisa klik "Join / Gabung" seperti pada bambar berikut :

![4](https://user-images.githubusercontent.com/111034379/184887311-c674a786-f89f-4971-9dc3-21ebfa6422b0.png)

Nanti akan muncul jendela baru, untuk menyetujui undangan sebagai "Collaborator". Klik Accept Invitation.

![5](https://user-images.githubusercontent.com/111034379/184887825-6b35cb8d-662e-4163-9f37-2f16ff720a13.png)

3. Masih sebagai Collaborator, buka halaman Github Repo, Git Clone proyek, dan cd ke direktori. Jangan jangan klik Fork it! Forking akan menyalin Repo baru ke halaman Github kamu, tetapi tapi karna kamu seorang "Collaborator" kamu tidak perlu melakukannya. Berikutnya copy link reponya seperti pada gambar berikut. linknya ada di menu "Code" yang berwarna hijau yaa.

![6](https://user-images.githubusercontent.com/111034379/184888530-b3fc8f24-f228-4b6a-ac71-55de83ec55dc.png)

# 4. Dan sekarang Anda siap untuk berkolaborasi!

# Langkah 3: Berkolaborasi
Saat kamu menggunakan git untuk mengerjakan proyek yang sama dengan banyak orang, ada satu aturan utama yang harus kamu ikuti:

# CABANG UTAMA HARUS SELALU DIPLOYABLE

Cara agar cabang (Branch) Master dapat digunakan adalah dengan membuat cabang (Branch) baru untuk fitur baru dan menggabungkannya (Merge) ke dalam Branch Master setelah selesai. Berikut ini langkahnya :

## Langkah berikutnya : Cabang

Untuk memulai, cabang (Branch) harus selalu mewakili fitur. Misalnya, jika kamu ingin menambahkan kemampuan bagi pengguna untuk masuk, Anda mungkin harus membuat cabang bernama "user_authentication" dan di cabang itu kamu hanya perlu memperbarui apa yang kamu perlukan untuk memungkinkan pengguna masuk.

Penting juga saat berkolaborasi agar tim kamu memilih fitur yang tidak memiliki kode yang tumpang tindih. Misalnya, kamu tidak boleh mengerjakan cabang "user_login" pada saat yang sama dengan rekan setim kamu mengerjakan cabang "user_logout" karena kemungkinan kamu mengerjakan file yang sama dan menulis kode yang tumpang tindih sangat tinggi .

## Buat cabang baru

caranya dengan masukkan perintah berikut 

> $ git branch [nama cabang]

lalu pindah ke cabang baru yang sudah di buat tadi dengan masukkan perintah berikut :

> $ git co -b create_user

"co" adalah kependekan dari "checkout" yang digunakan untuk berpindah antar cabang. Menambahkan "-b" dan nama di akhir membuat cabang baru dan kemudian pindah ke cabang baru itu untuk kita.

Kamu harus cek kamu berada di cabang mana dengan perintah:

> $ git branch

setelah kamu berada di cabang baru tersebut kamu bisa menambahkan projek baru.

# 4. TAMBAHKAN PROJEK BARU

disini kita akan mencoba menambah 1 file HTML sederhana, disini saya menggunakan VSCode.
Buat sebuah file html sederhana, dengan klik new file pada direktory reponya. di jendela editornya
ketik saja tanda seru "!" lalu Tab nanti otomatis akan menampilkan format script dasar HTML.

![7](https://user-images.githubusercontent.com/111034379/184894876-ed353682-4012-4748-b2ed-7aee42b0ded7.png)

seperti biasa, kita cek dulu dengan 

> $ git status (pastikan berada di branch yang benar)

> $ git add .


> $ git commit -m "menambahkan file daftar-peserta.html"


lalu kamu bisa push perubahannya ke remote, seperti pada gambar di bawah ini.

> $ git push 

![8](https://user-images.githubusercontent.com/111034379/184895615-4eb82365-dc38-4083-aba5-24fa5cb4091e.png)

Sekarang pergi ke halaman Repo Github. Kamu akan melihat cabang yang telah di push di bilah kuning di bagian atas halaman dengan tombol “Compare & pull request”. 
Catatan: Atau, kamu bisa memilih cabang / branch di menu drop-down “Branch:” dan pilih Branch yang baru saja kamu pushed up. kemudian kamu akan memiliki tombol “Pull request” di sisi kanan.

![9](https://user-images.githubusercontent.com/111034379/184896709-5e405d25-3f90-4871-8b7e-812ac31da869.png)

Klik “Compare & pull request”. Ini akan membawa Anda ke halaman “Open a pull request”. Dari sini, Anda harus menulis deskripsi singkat tentang apa yang sebenarnya Anda ubah. Dan Anda harus mengklik tab “Reviewers” tab dan memilih siapa pun yang diputuskan oleh tim kamu untuk “Merge Master”. Setelah selesai, klik “Create pull request”.

![reviewer](https://user-images.githubusercontent.com/111034379/184897873-358ee85f-7b85-4a27-8ce2-6b5e6cd8895c.png)
![10](https://user-images.githubusercontent.com/111034379/184898084-fa4c1849-ba87-42c6-9caf-000927ccc53f.png)

## Langkah berikutnya : Merging Pull Requests (Menggabungkan)

Perhatikan bahwa jika kamu seorang kolaborator, kamu dapat menggabungkan permintaan tarik kamu sendiri. Namun, sekali lagi, jika kamu bekerja dalam tim, lebih masuk akal jika satu orang melakukan semua penggabungan dan semua orang lainnya mengirimkan “Pull Requests” dan menetapkan “Master Merger” sebagai peninjau hanya untuk memastikan Anda berurusan dengan konflik gabungan apa pun satu cabang pada satu waktu.

Jadi, dengan asumsi kamu adalah orang yang bertanggung jawab untuk mengurus semua penggabungan dan seseorang telah menugaskan kamu sebagai "Peninjau" pada permintaan tarik, ketika kamu masuk ke Github, nanti kamu akan melihatpemberitahuan yang memberi tahu bahwa seseorang telah menugaskan kamu sebagai pengulas. kamu juga akan melihat bilah kuning yang menunjukkan salah satu rekan tim kamu sebagai “requested your review on this pull request.”."

Silakan dan klik tombol “Add your review”.

![add review](https://user-images.githubusercontent.com/111034379/184899568-090ac7a1-5fbc-4df4-8fe3-8f10bdda8d98.PNG)

lalu akan membawa kamu ke halaman Pull Request., kamu tidak perlu meninggalkan Ringkasan Ulasan yang bertele-tele dan terperinci.

Namun, jika Anda bekerja dari jarak jauh, ini akan menjadi alat utama kamu untuk memberi tahu pemohon jika mereka perlu melakukan perubahan atau jika kamu akan menggabungkan permintaan mereka.

![13](https://user-images.githubusercontent.com/111034379/184900247-ceb3a219-7681-40cf-bb64-b2fd426006ed.png)

Ketika Kamu mengklik “Submit review” pada tarik-turun “Review changes”, ulasan kamu sekarang akan ada sebagai komentar di pull request threadk.

Setelah itu buka bagian bawah the pull request dan klik “Merge pull request”.

![15](https://user-images.githubusercontent.com/111034379/184902043-cada1c46-c9b4-48d3-a2d4-946221d9cbc3.png)

Kemudian kamu akan melihat pesan “Pull request successfully merged and closed” dan tombol untuk  “Delete branch” yang harus Anda klik.

![16](https://user-images.githubusercontent.com/111034379/184902414-c0056e75-291e-4acb-8ad4-7f82ecd73f32.png)

# SELESAI!
