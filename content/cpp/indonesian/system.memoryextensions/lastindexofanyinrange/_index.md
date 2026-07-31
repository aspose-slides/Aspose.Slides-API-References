---
title: LastIndexOfAnyInRange()
second_title: Referensi API Aspose.Slides for C++
description: Menemukan kemunculan terakhir dari elemen apa pun dalam rentang yang ditentukan dalam sebuah span.
type: docs
weight: 261
url: /id/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi


Menemukan kemunculan terakhir dari elemen apa pun dalam rentang yang ditentukan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir dalam rentang, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fungsi


Menemukan kemunculan terakhir dari elemen apa pun dalam rentang yang ditentukan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
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

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir dalam rentang, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)