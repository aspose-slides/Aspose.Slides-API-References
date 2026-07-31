---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca sejumlah byte yang ditentukan dari aliran dasar dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 53
url: /id/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dasar dan menuliskannya ke dalam array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dasar dan menuliskannya ke dalam array byte yang ditentukan.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BufferedStream](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)