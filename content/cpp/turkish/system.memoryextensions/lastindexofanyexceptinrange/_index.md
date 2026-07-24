---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen aralık dışındaki herhangi bir öğenin bir span içinde son ortaya çıkışını bulur.
type: docs
weight: 248
url: /tr/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralık dışındaki herhangi bir öğenin bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

Aralık dışındaki son öğenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fonksiyon

Değiştirilebilir bir span içinde belirtilen aralık dışındaki herhangi bir öğenin son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
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

Aralık dışındaki son öğenin sıfır tabanlı indeksi, bulunamazsa -1

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)