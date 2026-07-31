---
title: Read()
second_title: Aspose.Slides untuk Referensi API C++
description: Membaca satu karakter dari aliran masukan.
type: docs
weight: 66
url: /id/system.io/binaryreader/read/
---
## BinaryReader::Read() metode

Membaca satu karakter dari aliran masukan.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Nilai Kembalian

Membaca karakter yang dikodekan dengan UTF-16; jika karakter yang dibaca diwakili oleh dua kode titik dalam enkoding UTF-16 maka hanya surrogat tinggi yang dikembalikan.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) metode

Membaca sejumlah byte yang ditentukan dari aliran masukan dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte untuk menuliskan byte yang dibaca |
| index | int | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | int | Jumlah byte yang akan dibaca |

### Nilai Kembalian

Jumlah byte yang dibaca

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) metode

Membaca sejumlah karakter yang ditentukan dari aliran masukan, mengonversinya ke enkoding UTF-16 dan menuliskan karakter UTF-16 yang dihasilkan ke array karakter yang ditentukan mulai dari posisi yang ditentukan.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Array karakter UTF-16 untuk menuliskan karakter yang dibaca dari aliran masukan |
| index | int | Indeks berbasis 0 dalam **buffer** tempat memulai penulisan |
| count | int | Jumlah karakter yang akan dibaca dari aliran |

### Nilai Kembalian

Jumlah karakter yang dibaca dari aliran masukan

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BinaryReader](../)
* Ruang nama [System::IO](../../)
* Library [Aspose.Slides](../../../)