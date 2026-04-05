# proyek-portofolio-ai
Portfolio project for 100Hires application, showcasing AI tool integration and research skills.
# Laporan Instalasi Tooling AI

Laporan ini berisi dokumentasi langkah-langkah instalasi Cursor IDE dan konfigurasi add-on yang diperlukan.

## 1. Alat yang Diinstal
Daftar perangkat lunak dan ekstensi yang berhasil dipasang:
* **Cursor IDE**: Editor kode utama berbasis AI.
* **Claude Code Add-on**: Ekstensi untuk integrasi model AI Claude dari Anthropic.
* **Codex Add-on**: Ekstensi untuk peningkatan fitur autocomplete dan saran kode.

## 2. Langkah Kerja
Berikut adalah urutan prosedur yang saya lakukan:
1. Mengunduh installer Cursor dari situs resmi dan menjalankan proses instalasi hingga selesai.
2. Membuka menu Extensions di Cursor dan mencari "Claude Code", kemudian melakukan login menggunakan akun terkait.
3. Mencari dan menginstal "Codex" dari marketplace ekstensi dan memastikan statusnya aktif.
4. Membuat repository baru di GitHub dengan akses publik.
5. Melakukan *cloning* repository tersebut ke folder lokal melalui terminal di Cursor.

## 3. Kendala dan Solusi
Selama proses instalasi, berikut adalah beberapa tantangan yang dihadapi:

| Kendala | Solusi |
| :--- | :--- |
| Gagal login pada ekstensi Claude Code. | Melakukan restart pada Cursor IDE dan memastikan browser default sudah login ke akun Anthropic. |
| Perintah `git push` ditolak (Permission Denied). | Melakukan konfigurasi ulang `git config --global user.email` dan menggunakan Personal Access Token. |
| Ekstensi Codex tidak muncul di sidebar. | Membuka Extension Settings dan mencentang opsi "Show in Sidebar". |
