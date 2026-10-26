---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Ortak ikili arama uygulaması.
type: docs
weight: 118
url: /tr/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) fonksiyonu


Ortak ikili arama uygulaması.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |
| TValue | Aranacak değerin tipi |
| TCompareFunc | Karşılaştırma için fonksiyon tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak span |
| value | const TValue\& | Aranacak değer |
| compareFunc | TCompareFunc | Değeri span öğesiyle karşılaştıran ve **int32_t** (-1, 0, 1) döndüren fonksiyon |

### Dönüş Değeri

[Index](../../system/index/) bulunan öğenin veya ekleme noktasının bitwise tamamlayıcısı

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Ad Alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)