---
title: HeapSort()
second_title: Aspose.Slides for C++ API Referansı
description: Anahtar-değer çiftleri üzerinde heap sort gerçekleştirir.
type: docs
weight: 79
url: /tr/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fonksiyon

Anahtar-değer çiftleri üzerinde heap sort gerçekleştirir.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| comparer | std::function\<int32_t(const TKey\&, const TKey\)> | [Comparison](../../system/comparison/) fonksiyonu anahtarlar için |

## İlgili

* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)