---
title: IndexOfAnyExceptInRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan indeks elemen pertama yang berada di luar rentang yang ditentukan dalam ReadOnlySpan<T>
type: docs
weight: 183
url: /id/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi

Menemukan indeks elemen pertama yang berada di luar rentang yang ditentukan dalam ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span untuk dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembali

Indeks berbasis nol dari elemen pertama di luar rentang, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fungsi

Menemukan indeks elemen pertama yang berada di luar rentang yang ditentukan dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span untuk dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembali

Indeks berbasis nol dari elemen pertama di luar rentang, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)