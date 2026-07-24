---
title: InsertionSort()
second_title: Aspose.Slides for C++ API Referansı
description: Anahtar-değer çiftleri üzerinde ekleme sıralaması gerçekleştirir.
type: docs
weight: 66
url: /tr/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fonksiyon

Anahtar-değer çiftleri üzerinde ekleme sıralaması gerçekleştirir.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların tipi |
| TValue | Değerlerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Sıralanacak anahtarların aralığı |
| values | [Span](../../system/span/)\<TValue\>\& | Sıralanacak değerlerin aralığı |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) anahtarlar için fonksiyon |

## Ayrıca Bakınız

* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)