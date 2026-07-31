---
title: ContainsAnyExcept()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah sebuah read-only span berisi elemen apa pun kecuali tiga nilai yang ditentukan.
type: docs
weight: 66
url: /id/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) fungsi

Memeriksa apakah sebuah read-only span berisi elemen apa pun kecuali tiga nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang akan dikecualikan |
| value1 | const T\& | Nilai kedua yang akan dikecualikan |
| value2 | const T\& | Nilai ketiga yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai-nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) fungsi

Memeriksa apakah sebuah span dapat diubah berisi elemen apa pun kecuali tiga nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah dan akan dicari |
| value0 | const T\& | Nilai pertama yang akan dikecualikan |
| value1 | const T\& | Nilai kedua yang akan dikecualikan |
| value2 | const T\& | Nilai ketiga yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai-nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah sebuah read-only span berisi elemen apa pun kecuali dua nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value0 | const T\& | Nilai pertama yang akan dikecualikan |
| value1 | const T\& | Nilai kedua yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai-nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) fungsi

Memeriksa apakah sebuah span dapat diubah berisi elemen apa pun kecuali dua nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah dan akan dicari |
| value0 | const T\& | Nilai pertama yang akan dikecualikan |
| value1 | const T\& | Nilai kedua yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai-nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) fungsi

Memeriksa apakah sebuah read-only span berisi elemen apa pun kecuali satu nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value | const T\& | Nilai yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) fungsi

Memeriksa apakah sebuah span dapat diubah berisi elemen apa pun kecuali satu nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah dan akan dicari |
| value | const T\& | Nilai yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang berbeda dari nilai yang ditentukan, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memeriksa apakah sebuah read-only span berisi elemen apa pun kecuali elemen-elemen dalam span lain.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam kedua span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span nilai yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang tidak terdapat dalam values, false sebaliknya

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memeriksa apakah sebuah span dapat diubah berisi elemen apa pun kecuali elemen-elemen dalam read-only span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam kedua span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah dan akan dicari |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Read-only span nilai yang akan dikecualikan |

### Nilai Kembali

true jika ada elemen yang tidak terdapat dalam values, false sebaliknya

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)