---
title: ContainsAnyInRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah span read-only berisi elemen apa pun dalam rentang yang ditentukan.
type: docs
weight: 92
url: /id/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah span read-only berisi elemen apa pun dalam rentang yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span (harus dapat dibandingkan) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span untuk pencarian |
| lowInclusive | const T\& | Batas bawah (inklusif) |
| highInclusive | const T\& | Batas atas (inklusif) |

### Nilai Kembali

true jika ada elemen dalam rentang yang ditemukan, false jika tidak

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah span yang dapat diubah berisi elemen apa pun dalam rentang yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span (harus dapat dibandingkan) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk pencarian |
| lowInclusive | const T\& | Batas bawah (inklusif) |
| highInclusive | const T\& | Batas atas (inklusif) |

### Nilai Kembali

true jika ada elemen dalam rentang yang ditemukan, false jika tidak

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)