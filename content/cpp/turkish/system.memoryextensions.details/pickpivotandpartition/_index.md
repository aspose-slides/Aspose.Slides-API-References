---
title: PickPivotAndPartition()
second_title: Aspose.Slides için C++ API Referansı
description: Pivot seçer ve hızlı sıralama için anahtar-değer çiftlerini bölümlendirir.
type: docs
weight: 105
url: /tr/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fonksiyon


Pivot seçer ve hızlı sıralama için anahtar-değer çiftlerini bölümlendirir.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların tipi |
| TValue | Değerlerin tipi |

### Bağımsız değişkenler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Bölümlendirilecek anahtar aralığı |
| values | [Span](../../system/span/)\<TValue\>\& | Bölümlendirilecek değer aralığı |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) işlevi anahtarlar için |

### Dönüş Değeri

Bölümlendirme sonrası pivot indeksi

## İlgili

* Sınıf [Span](../../system/span/)
* İsim Uzayı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)