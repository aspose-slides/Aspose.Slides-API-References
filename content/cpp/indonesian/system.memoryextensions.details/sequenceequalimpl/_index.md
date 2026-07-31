---
title: SequenceEqualImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah dua span sama mulai dari posisi yang ditentukan.
type: docs
weight: 27
url: /id/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) fungsi

Memeriksa apakah dua span sama mulai dari posisi yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama |
| start | const **int32_t** | Indeks awal pada span pertama |
| length | **int32_t** | Jumlah elemen yang dibandingkan |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua |

### Nilai Kembali

true jika rentang yang ditentukan sama, false jika tidak

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)