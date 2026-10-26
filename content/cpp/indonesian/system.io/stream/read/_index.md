---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 27
url: /id/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | Ukuran array stack |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Array stack byte untuk menuliskan byte yang dibaca |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan |
| count | **int32_t** | Jumlah byte yang akan dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Stream::Read(const System::Span\<uint8_t\>\&) metode

Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke span byte yang ditentukan.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Span byte untuk menuliskan byte yang dibaca |

### Nilai Kembali

Jumlah byte yang dibaca

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Stream](../)
* Kelas [Span](../../../system/span/)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)