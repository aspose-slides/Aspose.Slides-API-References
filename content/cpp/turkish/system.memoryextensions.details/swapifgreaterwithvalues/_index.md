---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides için C++ API Referansı
description: Karşılaştırma koşulu sağlandığında anahtar-değer çiftlerini değiştirir.
type: docs
weight: 53
url: /tr/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) fonksiyon

Karşılaştırma koşulu sağlandığında anahtar-değer çiftlerini değiştirir.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların türü |
| TValue | Değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Anahtarların aralığı |
| values | [Span](../../system/span/)\<TValue\>\& | Değerlerin aralığı |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) anahtarlar için fonksiyon |
| i | **int32_t** | Karşılaştırılacak ilk dizin |
| j | **int32_t** | Karşılaştırılacak ikinci dizin |

## Bakınız

* Sınıf [Span](../../system/span/)
* Ad Alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)