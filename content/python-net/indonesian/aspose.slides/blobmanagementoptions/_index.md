---
title: BlobManagementOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions kelas

Mewakili opsi yang dapat digunakan untuk mengelola aturan penanganan BLOB dan pengaturan BLOB lainnya.

Tipe BlobManagementOptions menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides/blobmanagementoptions/__init__/#) | Membuat opsi manajemen blob default baru. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/id/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Properti ini menentukan apakah sebuah instansi dari Presentation kelas dapat menjadi pemilik sumber - file <br/> atau stream selama masa hidup instansi. Jika instansi menjadi pemilik, ia mengunci sumber. Ini membantu <br/> meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (stream atau file) <br/> tidak dapat diubah selama masa hidup instansi Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan <br/> mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file.<br/> Semua file akan dihapus setelah pekerjaan dengan presentasi selesai. |
| [`temp_files_root_path`](/slides/python-net/id/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Jalur root dimana file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. <br/> Proses hosting harus memiliki izin untuk <br/> membuat file dan folder di sana. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/id/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB<br/> dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara)<br/> yang digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan<br/> properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)