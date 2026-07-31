---
title: ContainsAnyExceptInRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah span baca-saja mengandung elemen apa pun di luar rentang yang ditentukan.
type: docs
weight: 79
url: /id/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah span baca-saja mengandung elemen apa pun di luar rentang yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span (harus dapat dibandingkan) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| lowInclusive | const T\& | Batas bawah (inklusif) |
| highInclusive | const T\& | Batas atas (inklusif) |

### Nilai Kembali

true jika ditemukan elemen di luar rentang, false sebaliknya

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah span yang dapat diubah mengandung elemen apa pun di luar rentang yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span (harus dapat dibandingkan) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk dicari |
| lowInclusive | const T\& | Batas bawah (inklusif) |
| highInclusive | const T\& | Batas atas (inklusif) |

### Nilai Kembali

true jika ditemukan elemen di luar rentang, false sebaliknya

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)