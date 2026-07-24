---
title: Heapify()
second_title: Aspose.Slides for C++ API Referansı
description: Anahtar-değer çiftleri için yığın özelliğini korur.
type: docs
weight: 92
url: /tr/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) fonksiyon

Anahtar-değer çiftleri için yığın özelliğini korur.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların tipi |
| TValue | Değerlerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Yığındaki anahtarların aralığı |
| values | [Span](../../system/span/)\<TValue\>\& | Yığındaki değerlerin aralığı |
| n | **int32_t** | Yığının boyutu |
| i | **int32_t** | [Index](../../system/index/) heapify edilecek konum |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) anahtarlar için fonksiyon |

## Ayrıca bakınız

* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)