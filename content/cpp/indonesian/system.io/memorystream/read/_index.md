---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 79
url: /id/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** tempat mulai menulis |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** tempat mulai menulis |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [MemoryStream](../)
* Ruang Nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)