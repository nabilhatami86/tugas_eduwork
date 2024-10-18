Berikut adalah `README.md` yang sudah menggabungkan semua perintah dan gambar menjadi satu bagian, dengan penjelasan untuk setiap langkah disertai gambar masing-masing:

```markdown
# Panduan Dasar Git

Ini adalah panduan dasar untuk menggunakan Git dalam proyek Anda. Setiap langkah berikut dilengkapi dengan contoh perintah dan tampilan gambar yang menunjukkan hasilnya.

## Langkah-langkah Dasar Git

### 1. Inisialisasi Git Repository

Untuk memulai menggunakan Git, pertama-tama Anda harus menginisialisasi repository Git pada folder proyek Anda.

```bash
git init
```

Tampilan dari hasil perintah `git init`:

![git init](./images/git-init.png)

---

### 2. Menambahkan File ke Staging Area

Setelah melakukan perubahan pada file, tambahkan file tersebut ke staging area menggunakan perintah berikut:

```bash
git add .
```

Tampilan dari hasil perintah `git add .`:

![git add](./images/git-add.png)

---

### 3. Melakukan Commit Perubahan

Setelah menambahkan file ke staging area, Anda bisa melakukan commit untuk menyimpan perubahan dengan pesan commit yang jelas.

```bash
git commit -m "Pesan commit"
```

Tampilan dari hasil perintah `git commit`:

![git commit](./images/git-commit.png)

---

### 4. Mengecek Status Repository

Untuk melihat status dari repository, apakah ada file yang belum di-track atau belum di-commit, gunakan perintah:

```bash
git status
```

Tampilan dari hasil perintah `git status`:

![git status](./images/git-status.png)

---

### 5. Menambahkan Remote Repository

Agar bisa menghubungkan repository lokal Anda dengan repository remote di GitHub atau layanan lain, tambahkan remote repository:

```bash
git remote add origin https://github.com/nabilcuy/tugas-eduwork.git
```

Tampilan dari hasil perintah `git remote add`:

![git remote](./images/git-remote.png)

---

### 6. Mengirimkan Perubahan ke Remote Repository

Setelah semua perubahan di-commit, Anda bisa mengirimkan perubahan tersebut ke remote repository dengan perintah:

```bash
git push origin main
```

Tampilan dari hasil perintah `git push`:

![git push](./images/git-push.png)

---

## Kesimpulan

Dengan mengikuti panduan di atas, Anda dapat mulai mengelola proyek dengan Git secara lebih terstruktur dan efisien. Setiap perintah Git yang digunakan telah dilengkapi dengan ilustrasi untuk memudahkan pemahaman.
```

Pastikan kamu menggabungkan semua file gambar (`git-init.png`, `git-add.png`, `git-commit.png`, `git-status.png`, `git-remote.png`, dan `git-push.png`) ke dalam folder `images` di dalam proyek, sehingga struktur foldernya terlihat seperti ini:

```
project-root/
│
├── README.md
└── images/
    ├── git_init.png
    ├── git_add.png
    ├── git_commit.png
    ├── git_status.png
    ├── git_remote.png
    └── git_push.png
```

Dengan struktur ini, semua gambar akan tampil dengan benar saat README.md dilihat melalui GitHub atau platform lain.
