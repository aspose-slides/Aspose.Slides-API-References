---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory properti
Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB
            dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara
            ) digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan
            properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.


### Catatan

Properti ini diabaikan jika [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) disetel ke false, karena memori kemudian
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
* kelas [`BlobManagementOptions`](/slides/python-net/id/aspose.slides/blobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)