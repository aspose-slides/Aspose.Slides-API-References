---
title: ContainsAny()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah rentang baca-saja mengandung salah satu dari dua nilai.
type: docs
weight: 53
url: /id/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Memeriksa apakah rentang baca-saja mengandung salah satu dari dua nilai.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk pencarian |
| value0 | const T\& | Nilai pertama yang dicari |
| value1 | const T\& | Nilai kedua yang dicari |

### Nilai Kembalian

true jika salah satu nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Memeriksa apakah rentang baca-saja mengandung salah satu dari tiga nilai.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk pencarian |
| value0 | const T\& | Nilai pertama yang dicari |
| value1 | const T\& | Nilai kedua yang dicari |
| value2 | const T\& | Nilai ketiga yang dicari |

### Nilai Kembalian

true jika salah satu nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function


Memeriksa apakah rentang yang dapat diubah mengandung salah satu dari dua nilai.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk pencarian |
| value0 | const T\& | Nilai pertama yang dicari |
| value1 | const T\& | Nilai kedua yang dicari |

### Nilai Kembalian

true jika salah satu nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Memeriksa apakah rentang yang dapat diubah mengandung salah satu dari tiga nilai.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk pencarian |
| value0 | const T\& | Nilai pertama yang dicari |
| value1 | const T\& | Nilai kedua yang dicari |
| value2 | const T\& | Nilai ketiga yang dicari |

### Nilai Kembalian

true jika salah satu nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Memeriksa apakah rentang baca-saja mengandung nilai apa pun dari rentang lain.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk pencarian |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang nilai-nilai yang dicari |

### Nilai Kembalian

true jika nilai dari values ditemukan dalam span, false jika tidak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Memeriksa apakah rentang yang dapat diubah mengandung nilai apa pun dari rentang baca-saja.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk pencarian |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang baca-saja nilai-nilai yang dicari |

### Nilai Kembalian

true jika nilai dari values ditemukan dalam span, false jika tidak

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)