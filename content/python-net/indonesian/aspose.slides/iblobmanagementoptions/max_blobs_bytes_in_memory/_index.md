---
title: max_blobs_bytes_in_memory property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory properti
Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB
            dimuat ke dalam memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file
            sementara) dipakai. Menyimpan BLOB dalam memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan
            properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.


### Catatan

Properti ini diabaikan jika [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) diatur ke false, karena memori saat itu
            menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB dalam memori tidak berpengaruh.

### Definisi:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Lihat Juga
* kelas [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)