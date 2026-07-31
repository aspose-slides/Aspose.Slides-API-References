---
title: set_MaxBlobsBytesInMemory()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file temporer) yang digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.
type: docs
weight: 92
url: /id/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metode

Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file temporer) yang digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Keterangan

Nilai ini diabaikan jika [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) diatur ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB dalam memori tidak berpengaruh.  

Nilai default adalah 629.145.600 byte (600 MB).  

Anda dapat mengatur properti ini ke nol, tetapi jumlah memori minimum kecil tetap akan disisihkan. 

## Lihat Juga

* Kelas [IBlobManagementOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)