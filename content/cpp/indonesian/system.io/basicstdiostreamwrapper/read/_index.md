---
title: Read()
second_title: Aspose.Slides untuk Referensi API C++
description: Jika mode pembungkus adalah biner, membaca jumlah byte yang ditentukan dari aliran, jika tidak membaca jumlah karakter yang ditentukan dan mengonversinya ke tipe uint8_t. Menulis hasil pembacaan ke array byte yang ditentukan.
type: docs
weight: 66
url: /id/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Jika mode pembungkus adalah biner, membaca jumlah byte yang ditentukan dari aliran, jika tidak membaca jumlah karakter yang ditentukan dan mengonversinya ke tipe **uint8_t**. Menulis hasil pembacaan ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menulis byte yang dibaca ke |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembalian

Jumlah byte atau karakter yang dibaca

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca jumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte untuk menulis byte yang dibaca ke |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembalian

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BasicSTDIOStreamWrapper](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)