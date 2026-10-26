---
title: SequenceCompareTo()
second_title: Aspose.Slides untuk Referensi API C++
description: Membandingkan dua ReadOnlySpans secara leksikografis.
type: docs
weight: 313
url: /id/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Membandingkan dua ReadOnlySpan secara leksikografis.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama untuk dibandingkan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua untuk dibandingkan |

### Nilai Kembali

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Membandingkan [Span](../../system/span/) dan [ReadOnlySpan](../../system/readonlyspan/) secara leksikografis.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) untuk dibandingkan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) untuk dibandingkan |

### Nilai Kembali

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fungsi

Membandingkan [ReadOnlySpan](../../system/readonlyspan/) dan [Span](../../system/span/) secara leksikografis.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) untuk dibandingkan |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) untuk dibandingkan |

### Nilai Kembali

- 1 if span < other, 0 if span == other, 1 if span > other

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)