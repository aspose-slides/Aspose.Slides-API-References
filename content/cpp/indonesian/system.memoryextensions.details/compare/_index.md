---
title: Compare()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua smart pointer.
type: docs
weight: 1
url: /id/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) fungsi

Membandingkan dua smart pointer.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe smart pointer pertama |
| U | Tipe smart pointer kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer pertama |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Smart pointer kedua |

### Nilai Kembali

[Comparison](../../system/comparison/) hasil (0 jika sama, -1 jika a < b, 1 jika a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) fungsi

Membandingkan dua nilai aritmetik.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe aritmetik |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const T\& | Nilai pertama |
| b | const T\& | Nilai kedua |

### Nilai Kembali

[Comparison](../../system/comparison/) hasil (0 jika sama, -1 jika a < b, 1 jika a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) fungsi

Membandingkan smart pointer dengan nilai.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang ditunjuk oleh smart pointer |
| U | Tipe nilai |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Nilai |

### Nilai Kembali

[Comparison](../../system/comparison/) hasil (0 jika sama, -1 jika a < b, 1 jika a > b)

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Ruang nama [System::MemoryExtensions::Details](../)
* Pustaka [Aspose.Slides](../../)