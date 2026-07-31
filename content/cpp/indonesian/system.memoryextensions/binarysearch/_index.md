---
title: BinarySearch()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan pencarian biner pada span yang terurut.
type: docs
weight: 14
url: /id/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) fungsi

Melakukan pencarian biner pada span yang terurut.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparable | Tipe nilai yang dapat dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span terurut untuk dicari |
| comparable | const TComparable\& | Nilai yang akan dicari |

### Nilai Kembali

[Index](../../system/index/) elemen yang ditemukan, atau komplemen bitwise dari titik sisipan jika tidak ditemukan

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fungsi

Melakukan pencarian biner pada span yang terurut menggunakan pembanding khusus.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparer | Tipe pembanding |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span terurut untuk dicari |
| value | const T\& | Nilai yang akan dicari |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pembanding yang akan digunakan untuk perbandingan |

### Nilai Kembali

[Index](../../system/index/) elemen yang ditemukan, atau komplemen bitwise dari titik sisipan jika tidak ditemukan

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) fungsi

Melakukan pencarian biner pada span yang terurut yang dapat diubah.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparable | Tipe nilai yang dapat dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span terurut yang dapat diubah untuk dicari |
| comparable | const TComparable\& | Nilai yang akan dicari |

### Nilai Kembali

[Index](../../system/index/) elemen yang ditemukan, atau komplemen bitwise dari titik sisipan jika tidak ditemukan

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fungsi

Melakukan pencarian biner pada span yang terurut yang dapat diubah menggunakan pembanding khusus.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TComparer | Tipe pembanding |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span terurut yang dapat diubah untuk dicari |
| value | const T\& | Nilai yang akan dicari |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pembanding yang akan digunakan untuk perbandingan |

### Nilai Kembali

[Index](../../system/index/) elemen yang ditemukan, atau komplemen bitwise dari titik sisipan jika tidak ditemukan

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)