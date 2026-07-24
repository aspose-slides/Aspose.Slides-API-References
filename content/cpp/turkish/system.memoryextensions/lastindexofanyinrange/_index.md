---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen aralık içinde bir span içinde herhangi bir öğenin son oluşumunu bulur.
type: docs
weight: 261
url: /tr/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon


Belirtilen aralık içindeki herhangi bir öğenin son oluşumunu bir span içinde bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İçinde aranacak span |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralık içindeki son öğenin sıfır tabanlı indeksi, bulunamazsa -1 döner

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonksiyon


Belirtilen aralık içindeki herhangi bir öğenin son oluşumunu değiştirilebilir bir span içinde bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İçinde aranacak span |
| lowInclusive | const T\& | Aralığın alt sınırı (dahil) |
| highInclusive | const T\& | Aralığın üst sınırı (dahil) |

### Dönüş Değeri

Aralık içindeki son öğenin sıfır tabanlı indeksi, bulunamazsa -1 döner

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad Alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)