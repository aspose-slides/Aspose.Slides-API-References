---
title: Read()
second_title: Aspose.Slides untuk Referensi API C++
description: Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 144
url: /id/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [UnmanagedMemoryStream](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)