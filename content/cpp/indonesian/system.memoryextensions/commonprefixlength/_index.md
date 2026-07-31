---
title: CommonPrefixLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan panjang awalan bersama antara dua rentang.
type: docs
weight: 27
url: /id/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi


Menemukan panjang awalan bersama antara dua rentang.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang pertama |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang kedua |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi


Menemukan panjang awalan bersama antara rentang yang dapat diubah dan rentang hanya-baca.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang hanya-baca |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) fungsi


Menemukan panjang awalan bersama antara dua rentang yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah pertama |
| other | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah kedua |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fungsi


Menemukan panjang awalan bersama antara dua rentang menggunakan pembanding kesetaraan khusus.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |
| TEqualityComparer | Tipe pembanding kesetaraan |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang pertama |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang kedua |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Pembanding kesetaraan yang digunakan untuk perbandingan elemen |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fungsi


Menemukan panjang awalan bersama antara rentang yang dapat diubah dan rentang hanya-baca menggunakan pembanding kesetaraan khusus.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |
| TEqualityComparer | Tipe pembanding kesetaraan |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang hanya-baca |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Pembanding kesetaraan yang digunakan untuk perbandingan elemen |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fungsi


Menemukan panjang awalan bersama antara dua rentang yang dapat diubah menggunakan pembanding kesetaraan khusus.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam rentang |
| TEqualityComparer | Tipe pembanding kesetaraan |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah pertama |
| other | const [Span](../../system/span/)\<T\>\& | Rentang yang dapat diubah kedua |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Pembanding kesetaraan yang digunakan untuk perbandingan elemen |

### Nilai Kembali

Jumlah elemen yang cocok di awal kedua rentang

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)