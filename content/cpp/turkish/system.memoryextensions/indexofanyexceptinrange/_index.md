---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen aralığın dışındaki ilk öğenin indeksini bir ReadOnlySpan<T> içinde bulur
type: docs
weight: 183
url: /tr/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Belirtilen aralığın dışındaki ilk öğenin indeksini bir ReadOnlySpan<T> içinde bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak aralık |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralığın dışındaki ilk öğenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function


Belirtilen aralığın dışındaki ilk öğenin indeksini bir Span<T> içinde bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak aralık |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralığın dışındaki ilk öğenin sıfır tabanlı indeksi, bulunamazsa -1

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)