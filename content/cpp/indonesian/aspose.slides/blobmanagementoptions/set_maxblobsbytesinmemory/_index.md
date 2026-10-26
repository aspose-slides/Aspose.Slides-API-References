---
title: set_MaxBlobsBytesInMemory()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menjaga BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.
type: docs
weight: 92
url: /id/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metode

Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) yang digunakan. Menjaga BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Catatan

Nilai ini diabaikan jika [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) disetel ke false, karena memori saat itu menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB dalam memori tidak berpengaruh.

Nilai default adalah 629,145,600 byte (600 MB).

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum tetap akan dipertahankan.

## Lihat Juga

* Kelas [BlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)