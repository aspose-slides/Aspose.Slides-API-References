---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca satu karakter dari aliran.
type: docs
weight: 40
url: /id/system.io/stringreader/read/
---
## StringReader::Read() metode


Membaca satu karakter dari aliran.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Nilai Kembali

Karakter yang dibaca atau -1 jika tidak ada karakter yang dibaca

## StringReader::Read(ArrayPtr\<char_t\>, int, int) metode


Membaca sejumlah karakter yang ditentukan dari aliran ke array karakter yang ditentukan mulai dari posisi yang ditentukan.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Array karakter untuk menulis karakter yang dibaca dari aliran ke |
| index | int | Indeks berbasis 0 dalam **buffer** tempat memulai penulisan |
| count | int | Jumlah karakter yang akan dibaca dari aliran |

### Nilai Kembali

Jumlah karakter yang dibaca dari aliran

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [StringReader](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)