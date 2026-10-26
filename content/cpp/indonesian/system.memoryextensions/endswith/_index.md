---
title: EndsWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah ReadOnlySpan<T> diakhiri dengan satu nilai.
type: docs
weight: 131
url: /id/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function


Menentukan apakah sebuah ReadOnlySpan<T> diakhiri dengan satu nilai.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan diperiksa |
| value | const T\& | Nilai yang diperiksa di akhir span |

### Nilai Kembali

true jika span diakhiri dengan nilai, false jika tidak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Menentukan apakah sebuah ReadOnlySpan<T> diakhiri dengan ReadOnlySpan<T> lain.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang diperiksa di akhir span target |

### Nilai Kembali

true jika span diakhiri dengan span nilai, false jika tidak

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Menentukan apakah sebuah Span<T> diakhiri dengan sebuah ReadOnlySpan<T>.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang diperiksa di akhir span target |

### Nilai Kembali

true jika span diakhiri dengan span nilai, false jika tidak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Menentukan apakah sebuah ReadOnlySpan<T> diakhiri dengan sebuah Span<T>.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan diperiksa |
| value | const [Span](../../system/span/)\<T\>\& | Span yang diperiksa di akhir span target |

### Nilai Kembali

true jika span diakhiri dengan span nilai, false jika tidak

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function


Menentukan apakah sebuah Span<T> diakhiri dengan Span<T> lain.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan diperiksa |
| value | const [Span](../../system/span/)\<T\>\& | Span yang diperiksa di akhir span target |

### Nilai Kembali

true jika span diakhiri dengan span nilai, false jika tidak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Menentukan apakah sebuah ReadOnlySpan<char16_t> diakhiri dengan nilai yang ditentukan menggunakan StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Nilai yang diperiksa di akhir span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Jenis perbandingan string yang digunakan |

### Nilai Kembali

true jika span diakhiri dengan nilai, false jika tidak

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)