---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 196
url: /id/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode


Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte tempat byte yang dibaca akan ditulis. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembalian

Jumlah byte yang dibaca.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode


Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte tempat menuliskan byte yang dibaca ke sana |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| size | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembalian

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [NetworkStream](../)
* Ruang Nama [System::Net::Sockets](../../)
* Pustaka [Aspose.Slides](../../../)