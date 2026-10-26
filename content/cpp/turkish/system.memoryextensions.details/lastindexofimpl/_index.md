---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Bir span içinde bir değerin son indeksini bulur.
type: docs
weight: 14
url: /tr/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) fonksiyonu


Bir span içinde bir değerin son indeksini bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) aramak için |
| length | **int32_t** | Aranacak uzunluk |
| value | const T\& | Bulunacak değer |

### Dönüş Değeri

Değerin son indeksi, bulunamazsa -1

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Ad Alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)