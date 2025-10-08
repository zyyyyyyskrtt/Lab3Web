# Tugas Praktikum 3
**Nama:** Razy Al Farisi  
**Kelas:** TI.24.A5  
**Mata Kuliah:** Pemrograman Web 1


## 📘 Deskripsi Singkat
Repositori ini berisi latihan dasar pembuatan elemen-elemen HTML lanjutan seperti **List**, **Table**, dan **Form**.  
Tujuan proyek ini adalah memahami cara menampilkan data dan input pengguna menggunakan berbagai struktur HTML yang umum digunakan dalam pengembangan web.

---

## 🗂️ Daftar File

### 1. `list-description.html`
Menampilkan **Description List** atau daftar deskriptif menggunakan elemen `<dl>`, `<dt>`, dan `<dd>` untuk menampilkan daftar fakultas dan program studi.

**Struktur Utama:**
```html
<dl>
  <dt>Fakultas Teknik</dt>
  <dd>Teknik Informatika</dd>
  <dd>Teknik Industri</dd>
  <dd>Teknik Lingkungan</dd>
</dl>
```

**Tujuan:** Menunjukkan penggunaan *description list* untuk menjelaskan item utama dan sub-itemnya.

---

### 2. `table.html`
Berisi contoh **tabel HTML** sederhana untuk menampilkan data dalam format baris dan kolom.

**Elemen yang digunakan:**
- `<table>` : Membuat tabel  
- `<thead>` : Menentukan bagian kepala tabel  
- `<tbody>` : Menentukan isi tabel  
- `<tr>` : Baris tabel  
- `<th>` dan `<td>` : Kolom tabel  

**Contoh Struktur:**
```html
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
  </tbody>
</table>
```

**Tujuan:** Menampilkan data terstruktur secara rapi dalam bentuk tabel.

---

### 3. `form.html`
Berisi contoh **formulir HTML** untuk menerima input dari pengguna seperti nama, alamat, dan jenis kelamin.

**Elemen yang digunakan:**
- `<form>` : Wadah utama form  
- `<fieldset>` & `<legend>` : Mengelompokkan bagian form  
- `<input type="text">` : Input teks (nama)  
- `<textarea>` : Input teks panjang (alamat)  
- `<input type="radio">` : Pilihan jenis kelamin  

**Contoh Struktur:**
```html
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <label for="nama">Nama</label>
    <input type="text" id="nama" name="nama">
  </fieldset>
</form>
```

**Tujuan:** Memahami cara mengirim data pengguna melalui form menggunakan metode POST.

---

### 4. `list.html`
Berisi tiga jenis daftar berbeda:
1. **Ordered List (`<ol>`)** – Daftar bernomor  
2. **Unordered List (`<ul>`)** – Daftar berpoin  
3. **Description List (`<dl>`)** – Daftar penjelasan  

**Contoh Struktur:**
```html
<ol>
  <li>Pemrograman Web</li>
  <li>Sistem Informasi</li>
</ol>

<ul type="square">
  <li>Jaringan Komputer</li>
  <li>Struktur Data</li>
</ul>
```

**Tujuan:** Menunjukkan perbedaan fungsi dan tampilan dari tiga jenis list pada HTML.

---
