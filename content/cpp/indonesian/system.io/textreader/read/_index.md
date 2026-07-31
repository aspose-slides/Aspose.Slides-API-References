---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca satu karakter dari aliran.
type: docs
weight: 40
url: /id/system.io/textreader/read/
---
## TextReader::Read() metode

Membaca satu karakter dari aliran.

```cpp
virtual int System::IO::TextReader::Read()
```

### Nilai Kembali

Karakter yang dibaca dengan enkoding UTF-16; jika karakter yang dibaca direpresentasikan oleh dua kode titik dalam enkoding UTF-16 maka hanya surrogate tinggi yang dikembalikan.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metode

Membaca sejumlah karakter yang ditentukan dari aliran dan menuliskannya ke array karakter yang ditentukan mulai dari posisi yang ditentukan.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Array karakter UTF-16 untuk menulis karakter yang dibaca dari aliran |
| index | int | Indeks berbasis 0 dalam **buffer** tempat memulai penulisan |
| count | int | Jumlah karakter yang akan dibaca dari aliran |

### Nilai Kembali

Jumlah karakter yang dibaca dari aliran

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [TextReader](../)
* Ruang Nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)