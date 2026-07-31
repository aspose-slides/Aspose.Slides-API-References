---
title: get_MaxBlobsBytesInMemory()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.
type: docs
weight: 79
url: /id/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metode


Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Keterangan


Nilai ini diabaikan jika [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) diatur ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB dalam memori tidak berpengaruh. 

Nilai default adalah 629,145,600 byte (600 MB). 

Anda dapat menetapkan properti ini ke nol, tetapi sejumlah kecil memori minimum masih akan dicadangkan. 
## Lihat Juga

* Kelas [BlobManagementOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)