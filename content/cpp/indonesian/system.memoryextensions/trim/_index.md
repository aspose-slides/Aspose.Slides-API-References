---
title: Trim()
second_title: Referensi API Aspose.Slides untuk C++
description: Memangkas elemen yang ditentukan dari kedua ujung span yang bertipe.
type: docs
weight: 365
url: /id/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) fungsi

Memangkas elemen yang ditentukan dari kedua ujung span yang bertipe.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dipangkas |
| trimElement | T | Elemen yang akan dipangkas |

### Nilai Kembalian

Span baru dengan elemen yang ditentukan dipangkas dari kedua ujung

## System::MemoryExtensions::Trim(Span\<T\>\&, T) fungsi

Memangkas elemen yang ditentukan dari kedua ujung span yang bertipe dapat diubah.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk dipangkas |
| trimElement | T | Elemen yang akan dipangkas |

### Nilai Kembalian

Span baru dengan elemen yang ditentukan dipangkas dari kedua ujung

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memangkas elemen yang ditentukan dari kedua ujung span yang bertipe.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dipangkas |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elemen yang akan dipangkas |

### Nilai Kembalian

Span baru dengan elemen yang ditentukan dipangkas dari kedua ujung

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memangkas elemen yang ditentukan dari kedua ujung span yang bertipe dapat diubah.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk dipangkas |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elemen yang akan dipangkas |

### Nilai Kembalian

Span baru dengan elemen yang ditentukan dipangkas dari kedua ujung

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) fungsi

Memangkas karakter spasi dari kedua ujung span karakter.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span karakter yang akan dipangkas |

### Nilai Kembalian

Span baru dengan spasi dipangkas dari kedua ujung

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) fungsi

Memangkas karakter spasi dari kedua ujung span karakter yang dapat diubah.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span karakter yang dapat diubah untuk dipangkas |

### Nilai Kembalian

Span baru dengan spasi dipangkas dari kedua ujung

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)