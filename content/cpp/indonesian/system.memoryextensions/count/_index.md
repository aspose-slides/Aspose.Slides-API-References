---
title: Count()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung kemunculan nilai dalam rentang yang hanya-baca.
type: docs
weight: 118
url: /id/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) fungsi

Menghitung kemunculan nilai dalam ReadOnlySpan\<T\> yang hanya-baca.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk mencari |
| value | const T\& | Nilai untuk dihitung |

### Nilai Kembalian

Jumlah kali nilai muncul dalam rentang

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Menghitung kemunculan rentang dalam ReadOnlySpan\<T\> yang hanya-baca lainnya.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk mencari |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang untuk menghitung kemunculannya |

### Nilai Kembalian

Jumlah kali nilai muncul dalam rentang

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) fungsi

Menghitung kemunculan satu nilai dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang untuk mencari |
| value | const T\& | Nilai untuk menghitung kemunculannya |

### Nilai Kembalian

Jumlah kemunculan nilai dalam rentang

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Menghitung kemunculan ReadOnlySpan<T> dalam Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam rentang |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rentang untuk mencari |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rentang yang berisi nilai untuk menghitung kemunculannya |

### Nilai Kembalian

Jumlah kemunculan span nilai dalam span target

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)