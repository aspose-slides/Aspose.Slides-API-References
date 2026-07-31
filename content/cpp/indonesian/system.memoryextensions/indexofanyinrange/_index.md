---
title: IndexOfAnyInRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan indeks elemen pertama yang berada dalam rentang yang ditentukan dalam ReadOnlySpan<T>
type: docs
weight: 196
url: /id/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi

Menemukan indeks elemen pertama yang berada dalam rentang yang ditentukan dalam ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang yang akan dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembali

Indeks berbasis nol elemen pertama dalam rentang, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fungsi

Menemukan indeks elemen pertama yang berada dalam rentang yang ditentukan dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang yang akan dicari |
| lowInclusive | const T\& | Batas bawah rentang (inklusif) |
| highInclusive | const T\& | Batas atas rentang (inklusif) |

### Nilai Kembali

Indeks berbasis nol elemen pertama dalam rentang, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Pustaka [Aspose.Slides](../../)