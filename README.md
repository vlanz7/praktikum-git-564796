# Hoshizora Gakuin Website
Hoshizora Gakuin website merupakan sebuah website yang digunakan untuk mendaftar program LPK. Di dalam
website ini terdapat pengenalan seputar instansi kemudian program yang ditawarkannya.
## Open the Website
Lihat preview dari website yang dibuat dengan membuka file index.html yang ada di repository ini.
## Screenshot the Website
<img src="Screenshot (428).png" alt="tampilan_website">

## Screenshot Git Log
<img src="Screenshot (336).png" alt="git_log">

## Branch Protection Rule
<img src="Screenshot (374).png" alt="rule set 1">
<img src="Screenshot (375).png" alt="rule set 2">

## Tugas 1
* Langkah pertama dalam membuat website terhubung ke dalam github adalah dengan membuat repositorynya terlebih dahulu. Dalam halaman awal github, pilih new repository kemudian masukkan nama repositornya. Dibuat repository bernama praktikum-git-564796 yang disetel public dan ditambahkan readmenya. Setelah itu klik tombol hijau create di bawah. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (326).png" alt="new repository">

* Selanjutnya, hubungkan repository ini dengan lokal terminal menggunakan vs code. Buka vs code dan buat terminal baru kemudian ketikkan "https://github.com/vlanz7/praktikum-git-564796.git>> cd praktikum-git-564796". Tekan enter dan tunggu sampai lokal sudah terhubung dengan repository. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (327).png" alt="clone repository">

* Setelah itu, buat index.html yang berisi halaman website sederhana yang di dalamnya pula dibuat 5 commit. Commit pertama dibuat ketika file index.html pertama berhasil ditambahkan. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "init: first commit." Commit kedua ditambahkan ketika dibuatnya registration button. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: add registration now button." Commit ketiga ditambahkan ketika diubahnya warna Background. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "style: update background color." Commit keempat ditambahkan ketika dibuatnya program section. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: add program section." Terakhir, Commit kelima ditambahkan ketika diperbaikinya typo yang ada di halaman website. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "fix: correct typo in paragraph." Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (329).png" alt="commit 1">
<img src="Screenshot (332).png" alt="commit 2,3,4">
<img src="Screenshot (333).png" alt="commit 5">

* Selanjutnya, buat file .gitignore dan isi dengan nilai-nilai yang diperlukan(# macOS .DS_Store, # Log files *.log, # Node.js node_modules/, # Editor .vscode/ .idea/). Kemudian lakukan git add dan commit dengan "git commit -m "chore: add gitignore." Setelah itu, push perubahan ke main (git push origin main). Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (335).png" alt="gitignore">

* Terakhir, tuliskan perintah git log --online --graph dan screenshot hasilnya serta cantumkan hasilnya di readme seperti yang ada di bagian [Screenshot Git Log](#Screenshot-Git-Log). 

## Tugas 2
* Pada tugas 2, dibuatnya 3 buah branch yang terpisah dari main. Pertama, dibuat branch git checkout -b feature/navbar yang digunakan untuk menambahkan navbar pada halaman web. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: add navigation bar." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin feature/navbar. Kembalikan lagi pengerjaan ke main dengan mengetikkan git checkout main dan git pull origin main. Selanjutnya, dibuat branch kedua dengan git checkout -b feature/footer yang digunakan untuk menambahkan footer pada halaman web. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: add footer section." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin feature/footer. Selanjutnya, dibuat branch ketiga dengan git checkout -b hotfix/typo yang digunakan untuk mengoreksi typo yang ada pada halaman web. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "fix: correct typo on homepage." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin hotfix/typo. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (339).png" alt="branch 1">
<img src="Screenshot (341).png" alt="branch 2">
<img src="Screenshot (343).png" alt="branch 3">

* Selanjutnya buka github untuk membuat pull request. Di halaman awal repository, pergi ke tab bagian pull request yang ada di bawah nama repository. Setelah itu pilih tombol new pull request berwarna hijau yang ada. Setelah itu pilih branch mana yang ingin dibuat pull requestnya dan pilih create pull request dengan tombol yang juga berwarna hijau. Masukkan tittle Feature: Add Navigation Bar dan tambahkan deskripsinya. Sertakan juga label enhancement pada pull request ini. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (350).png" alt="PR 1">

* Lakukan hal yang sama untuk pull request branch berikutnya. Masukkan tittle Feature: Add footer section dan tambahkan deskripsinya. Sertakan juga label enhancement pada pull request ini. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (352).png" alt="PR 2">

* Lakukan hal yang sama pula untuk pull request branch terakhir. Masukkan tittle Hotfix: Fix Typo on Homepage dan tambahkan deskripsinya. Sertakan juga label bug pada pull request ini. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (354).png" alt="PR 3">

* Setelah itu, lakukan merge untuk semua pr (pull request) terhadap main. Gunakan Squash and merge untuk PR feature dan merge commit untuk PR hotfix. Hapus branch setelah proses merge berhasil. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (357).png" alt="Merge 1">
<img src="Screenshot (359).png" alt="Merge 2">
<img src="Screenshot (362).png" alt="Merge 3">

* Terakhir, pasang Branch protection rule untuk branch main agar proses penggabungan branch dengan main tidak dapat di push secara langsung, harus melewati pull request terlebih dahulu. Untuk mengatur tampilan ini, buka github dan pergi ke tab setting yang ada di bawah nama repository. Setelah itu pergi ke subtab branches dan pilih add classic branch protection rule. Atur pengaturan dengan mencekliskan bagian require a pull request before merging dan do not allow bypassing the above settings. Setelah itu pilih save changes. Untuk lebih jelasnya lagi, silakan lihat bagian [Branch Protection Rule](#Branch-Protection-Rule).

## Tugas 3
* Selanjutnya, buat dua branch (experiment/color-A dan experiment/color-B) yang di dalamnya dilakukan perubahan baris CSS yang sama dengan nilai yang berbeda. Pada experiment/color-A dilakukan perubahan background menjadi light green. Sedangkan di branch experiment/color-B dilakukan perubahan background menjadi alice blue. Lakukan git add, commit, dan push untuk masing-masing branch. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (397).png" alt="experiment A">
<img src="Screenshot (394).png" alt="experiment B">

* Setelah itu, lakukan pull request untuk menggabungkan (merge) branch A terhadap main. Dengan langkah yang sama seperti sebelumnya, masukkan tittle style: change background to light green dan tambahkan deskripsinya. Sertakan juga label enhancement pada pull request ini dan merge pull requestnya dengan merged commit. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (391).png" alt="Merge A">

* Dengan langkah yang sama, lakukan juga pull request untuk branch B. Masukkan tittle style: change background to alice blue dan tambahkan deskripsinya. Sertakan juga label enhancement pada pull request ini. Ketika mengklik tombol create pull request, maka pada bagian merge akan keluar peringatan bahwa branch ini memiliki konflik dan harus diselesaikan terlebih dahulu. Hal ini karena warna background untuk setiap branch berbeda sehingga diperlukannya kejelasan untuk menggunakan warna yang mana. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (393).png" alt="Merge B">

* Buka kembali vs code dan ketikkan git checkout experiment/color-B untuk tetap berada di branch B. Kemudian, pull branch B agar mendapatkan update terbaru dan ketikkan git merge main untuk melihat konflik secara langsung di index.html. Didapatkan bahwa pada tag body terdapat perbedaan penulisan warna sehingga terjadinya error. Untuk menyelesaikannya, hapus warna yang tidak diperlukan, misal light green, sehingga tampilan akhirnya hanya alice blue sendiri. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (398).png" alt="Resolve error 1">
<img src="Screenshot (399).png" alt="Resolve error 2">

* Ketikkan kembali "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "fix: resolve merge conflict for background color." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin experiment/color-B. Dengan ini, kembali lagi ke halaman github dan didapatkan bahwa konflik sudah terselesaikan. Lakukan merge untuk pr ini kemudian hapus branchnya ketika selesai. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (400).png" alt="Resolve error 3">
<img src="Screenshot (402).png" alt="Resolve error 4">

* Selanjutnya, buat kembali branch dengan nama feature/dark-mode. Lakukan 3 kali commit di dalamnya. Commit pertama dibuat ketika warna background diubah menjadi hitam. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: add dark background." Commit kedua ditambahkan ketika dibuatnya tulisan di dalam web menjadi putih. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "style: change text to color white." Commit ketiga ditambahkan ketika navbar diatur kembali untuk tema gelap. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "style: adjust navbar dark theme." Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (405).png" alt="dark mode commit">

* Selanjutnya gunakan interactive rebase dengan mengetikkan git rebase -i HEAD~3 di terminal. Setelah itu, ubah pengaturan commit dengan pick pada commit pertama, kemudian squash untuk commit setelahnya. Ketikkan esc dan :wq untuk keluar dari tampilan rebase setelah itu tekan enter. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (409).png" alt="dark mode commit 1">

* Setelah itu, akan terbuka lagi terminal yang menampilkan ini adalah kombinasi dari 3 commit. Lalu di bawahnya terdapat tulisan untuk ketiga commitnya. Hapus untuk bagian ke dua dan ke tiga, kemudian ganti penulisan commit pertama dengan feat: implement dark mode theme. Keluar dari tampilan terminal ini dengan menekan tombol esc, :wq, dan enter. Tampilan akan kembali ke terminal awal dan terdapat penulisan berhasil mengcommit ketiga baris dengan satu baris saja. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (410).png" alt="dark mode commit 2">
<img src="Screenshot (411).png" alt="dark mode commit 3">
<img src="Screenshot (412).png" alt="dark mode commit 4">

* Push branch tersebut, kemudian merge dengan menggunakan squash and merge pada pull request. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (413).png" alt="dark mode commit 5">
<img src="Screenshot (414).png" alt="dark mode commit 6">

## Tugas 4
* Langkah selanjutnya adalah dengan membuat 3 issue berbeda. Issues dibuat dengan membuka tab issue yang ada di bawah nama repository kemudian pilih new issue. Buat tittle dan deskripsi issue dan pilih create issue. Dibuat issue pertama dengan menyatakan bahwa navbar belum responsive. Dibuat juga issue kedua bahwa footer masih kurang rapi. Terakhir, dibuat issue bahwa dark mode perlu disesuaikan kembali. Untuk lebih jelasnya, silakan lihat gambar berikut:
<img src="Screenshot (416).png" alt="dark mode commit 2">
<img src="Screenshot (417).png" alt="dark mode commit 3">
<img src="Screenshot (418).png" alt="dark mode commit 4">

* Lakukan penyelesain untuk setiap issue. Pertama buat branch responsive layout dan tambahkan kode java untuk ukuran layar mobile agar website responsive. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: improve navbar layout." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin feature/responsive-layout. Pergi ke halaman github dan buat pull requestnya. Berikan title feat: improve navbar layout dan berikan closes#13 di deskripsinya kemudian label enhancment. Merge dengan squash kemudian hapus branchnya ketika sudah selesai. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (419).png" alt="Resolve issue 1">
<img src="Screenshot (421).png" alt="Resolve issue 1">

* Selanjutnya buat branch update footer layout dan tambahkan kode java untuk membuat tampilan footer lebih baik. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: improve footer layout." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin feature/update-footer-layout. Pergi ke halaman github dan buat pull requestnya. Berikan title feat: improve footer layout dan berikan closes#14 di deskripsinya kemudian label enhancment. Merge dengan squash kemudian hapus branchnya ketika sudah selesai. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (422).png" alt="Resolve issue 2">
<img src="Screenshot (423).png" alt="Resolve issue 2">

* Terakhir buat branch update dark mode dan tambahkan kode java untuk membuat tampilan dark mode lebih baik. Ketikkan "git add ." dan dilanjutkan dengan nama commitnya, "git commit -m "feat: improve dark mode." Setelah itu, push branch ke githubnya dengan mengetikkan git push origin feature/update-dark-mode. Pergi ke halaman github dan buat pull requestnya. Berikan title feat: improve dark mode dan berikan closes#15 di deskripsinya kemudian label enhancment. Merge dengan squash kemudian hapus branchnya ketika sudah selesai. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (424).png" alt="Resolve issue 3">
<img src="Screenshot (425).png" alt="Resolve issue 3">

* Selanjutnya adalah dengan menambahkan release versi v.1.0.0 di github. Pada halaman awal repository, cari bagian release yang ada di samping kanan tampilan dan di bawah about. Setelah itu tekan create new release dan masukkan keterangannya. Dimasukkan pula tag dengan v.1.0.0 dan title Release v.1.0.0, kemudian pilih publish release. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (427).png" alt="Release version">

* Terakhir, invite collaborators dengan memasukkan nama akun dosen dan asprak. Untuk lebih jelasnya lagi, silakan lihat gambar berikut:
<img src="Screenshot (429).png" alt="Invite Collaborator">