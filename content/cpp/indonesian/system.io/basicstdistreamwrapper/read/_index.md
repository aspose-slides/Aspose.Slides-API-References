---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika mode pembungkusan adalah biner, membaca sejumlah byte yang ditentukan dari aliran, jika tidak membaca sejumlah karakter yang ditentukan dan mengonversinya ke tipe uint8_t. Menulis hasil pembacaan ke array byte yang ditentukan.
type: docs
weight: 66
url: /id/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Jika mode pembungkusan adalah biner, membaca sejumlah byte yang ditentukan dari aliran, jika tidak membaca sejumlah karakter yang ditentukan dan mengonversinya ke tipe **uint8_t**. Menulis hasil pembacaan ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menulis byte yang dibaca ke |
| offset | **int32_t** | Posisi berbasis 0 di **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte atau karakter yang dibaca

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte untuk menulis byte yang dibaca ke |
| offset | **int32_t** | Posisi berbasis 0 di **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)