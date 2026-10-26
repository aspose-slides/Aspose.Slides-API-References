---
title: IntroSort()
second_title: Aspose.Slides for C++ API Referansı
description: Anahtar-değer çiftleri için introsort algoritmasının dahili uygulaması.
type: docs
weight: 40
url: /tr/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) fonksiyon

Anahtar-değer çiftleri için introsort algoritmasının dahili uygulaması.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların türü |
| TValue | Değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Sıralanacak anahtarların aralığı |
| values | [Span](../../system/span/)\<TValue\>\& | Sıralanacak değerlerin aralığı |
| depthLimit | **int32_t** | Heapsort'a geçmeden önceki maksimum özyineleme derinliği |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) anahtarlar için fonksiyon |

## Ayrıca bakınız

* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)