---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen aralıktaki ilk öğenin indeksini bir ReadOnlySpan<T> içinde bulur
type: docs
weight: 196
url: /tr/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralıktaki ilk elemanın indeksini bir ReadOnlySpan<T> içinde bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralık içinde bulunan ilk öğenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralıktaki ilk elemanın indeksini bir Span<T> içinde bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralık içinde bulunan ilk öğenin sıfır tabanlı indeksi, bulunamazsa -1

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)