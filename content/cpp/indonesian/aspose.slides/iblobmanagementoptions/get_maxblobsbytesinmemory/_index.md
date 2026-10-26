---
title: get_MaxBlobsBytesInMemory()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menjaga BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.
type: docs
weight: 79
url: /id/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metode

Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menjaga BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Catatan

Nilai ini diabaikan jika [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) disetel ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB di memori tidak berpengaruh. 

Nilai defaultnya adalah 629,145,600 byte (600 MB). 

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum masih akan disediakan. 

## Lihat Juga

* Kelas [IBlobManagementOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)