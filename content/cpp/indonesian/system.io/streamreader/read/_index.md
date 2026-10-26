---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca satu karakter dari aliran.
type: docs
weight: 40
url: /id/system.io/streamreader/read/
---
## StreamReader::Read() method


Membaca satu karakter dari aliran.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Nilai Kembalian

Karakter yang dibaca dienkode dengan UTF-16; jika karakter yang dibaca direpresentasikan oleh dua kode poin dalam enkoding UTF-16 maka hanya surrogat tinggi yang dikembalikan.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Membaca sejumlah karakter yang ditentukan dari aliran, mengkonversinya ke enkoding UTF-16 dan menulis karakter UTF-16 yang dihasilkan ke array karakter yang ditentukan dimulai pada posisi yang ditentukan.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Array karakter UTF-16 untuk menulis karakter yang dibaca dari aliran ke dalamnya |
| index | int | Indeks berbasis nol dalam **buffer** tempat penulisan dimulai |
| count | int | Jumlah karakter yang akan dibaca dari aliran |

### Nilai Kembalian

Jumlah karakter yang dibaca dari aliran

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [StreamReader](../)
* Namespace [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)