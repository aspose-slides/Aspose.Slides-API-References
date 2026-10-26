---
title: SequenceEqual()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah dua ReadOnlySpan berisi elemen yang identik dalam urutan yang sama.
type: docs
weight: 326
url: /id/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Menentukan apakah dua ReadOnlySpan berisi elemen yang identik dalam urutan yang sama.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama untuk dibandingkan |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua untuk dibandingkan |

### Nilai Kembali

true jika span memiliki panjang yang sama dan semua elemen sama, false jika tidak

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Menentukan apakah sebuah [Span](../../system/span/) dan [ReadOnlySpan](../../system/readonlyspan/) berisi elemen yang identik dalam urutan yang sama.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) untuk dibandingkan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) untuk dibandingkan |

### Nilai Kembali

true jika span memiliki panjang yang sama dan semua elemen sama, false jika tidak

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Menentukan apakah dua ReadOnlySpan berisi elemen yang sama menggunakan pembanding khusus.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparer | Tipe objek pembanding |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama untuk dibandingkan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua untuk dibandingkan |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer ke objek pembanding untuk perbandingan elemen |

### Nilai Kembali

true jika span memiliki panjang yang sama dan pembanding menganggap semua elemen sama, false jika tidak

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Menentukan apakah sebuah [Span](../../system/span/) dan [ReadOnlySpan](../../system/readonlyspan/) berisi elemen yang sama menggunakan pembanding khusus.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparer | Tipe objek pembanding |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) untuk dibandingkan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) untuk dibandingkan |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer ke objek pembanding untuk perbandingan elemen |

### Nilai Kembali

true jika span memiliki panjang yang sama dan pembanding menganggap semua elemen sama, false jika tidak

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)