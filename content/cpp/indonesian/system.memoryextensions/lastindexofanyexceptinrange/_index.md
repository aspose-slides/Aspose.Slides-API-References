---
title: LastIndexOfAnyExceptInRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan kejadian terakhir dari elemen mana pun di luar rentang yang ditentukan dalam sebuah span.
type: docs
weight: 248
url: /id/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Menemukan kejadian terakhir dari elemen mana pun di luar rentang yang ditentukan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembalian

Indeks berbasis nol dari elemen terakhir di luar rentang, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Menemukan kejadian terakhir dari elemen mana pun di luar rentang yang ditentukan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembalian

Indeks berbasis nol dari elemen terakhir di luar rentang, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)