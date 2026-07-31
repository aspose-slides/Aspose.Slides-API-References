---
title: LastIndexOfAnyExcept()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan kemunculan terakhir dari elemen apa pun kecuali tiga nilai yang ditentukan dalam sebuah span.
type: docs
weight: 235
url: /id/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali tiga nilai yang ditentukan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang dikecualikan |
| value1 | const T\& | Nilai kedua yang dikecualikan |
| value2 | const T\& | Nilai ketiga yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali tiga nilai yang ditentukan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang dikecualikan |
| value1 | const T\& | Nilai kedua yang dikecualikan |
| value2 | const T\& | Nilai ketiga yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali dua nilai yang ditentukan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang dikecualikan |
| value1 | const T\& | Nilai kedua yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali dua nilai yang ditentukan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang dikecualikan |
| value1 | const T\& | Nilai kedua yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali nilai yang ditentukan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value | const T\& | Nilai yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali nilai yang ditentukan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| value | const T\& | Nilai yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali nilai-nilai dari sebuah urutan dalam sebuah span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Urutan nilai yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali nilai-nilai dari sebuah urutan dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Urutan nilai yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

Menemukan kemunculan terakhir dari elemen apa pun kecuali nilai-nilai dari sebuah urutan yang dapat diubah dalam sebuah span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang akan dicari |
| values | const [Span](../../system/span/)\<T\>\& | Urutan nilai yang dikecualikan |

### Nilai Kembali

Indeks berbasis nol dari elemen terakhir yang tidak dikecualikan, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)