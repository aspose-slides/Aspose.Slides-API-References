---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan indeks nilai ReadOnlySpan<T> dalam ReadOnlySpan<T> lain
type: docs
weight: 144
url: /id/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Menemukan indeks nilai ReadOnlySpan<T> dalam ReadOnlySpan<T> lain

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span tempat pencarian |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |

### Nilai Kembalian

Indeks berbasis nol dari kemunculan pertama, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) fungsi

Menemukan indeks nilai tunggal dalam ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span tempat pencarian |
| value | const T\& | Nilai yang akan dicari |

### Nilai Kembalian

Indeks berbasis nol dari kemunculan pertama, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Menemukan indeks nilai ReadOnlySpan<T> dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span tempat pencarian |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |

### Nilai Kembalian

Indeks berbasis nol dari kemunculan pertama, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) fungsi

Menemukan indeks nilai tunggal dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span tempat pencarian |
| value | const T\& | Nilai yang akan dicari |

### Nilai Kembalian

Indeks berbasis nol dari kemunculan pertama, atau -1 jika tidak ditemukan

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fungsi

Menemukan indeks nilai ReadOnlySpan<char16_t> dalam ReadOnlySpan<char16_t> dengan StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span tempat pencarian |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Nilai yang akan dicari |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Tipe perbandingan string yang akan digunakan |

### Nilai Kembalian

Indeks berbasis nol dari kemunculan pertama, atau -1 jika tidak ditemukan

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)