---
title: IBlobManagementOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions kelas

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas - yaitu BLOB dapat berupa 
            audio, video, atau presentasi itu sendiri. Sejumlah teknik digunakan untuk mengoptimalkan konsumsi memori 
            saat bekerja dengan BLOB - yang sudah disimpan dalam presentasi atau dapat ditambahkan kemudian secara programatis. 
            Menggunakan [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions) Anda dapat mengubah berbagai aspek perilaku terkait penanganan BLOB 
            untuk masa hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation).

The IBlobManagementOptions type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber - file <br/>            atau aliran selama umur instance. Jika instance menjadi pemilik, ia mengunci sumber. Hal ini membantu <br/>            meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (aliran atau file) <br/>            tidak dapat diubah selama umur instance Presentation. Ini adalah contoh: |
| [`is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan <br/>            mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file.<br/>            Semua file akan dihapus setelah pekerjaan dengan presentasi selesai. |
| [`temp_files_root_path`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Jalur root tempat file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. <br/>            Proses hosting harus memiliki izin untuk <br/>            membuat file dan folder di sana. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB<br/>            dimuat ke dalam memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara)<br/>            yang digunakan. Menyimpan BLOB dalam memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan<br/>            properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda. |


### Lihat Juga
* kelas [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)