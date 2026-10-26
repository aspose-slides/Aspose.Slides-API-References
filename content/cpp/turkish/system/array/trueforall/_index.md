---
title: TrueForAll()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizideki tüm elemanların, belirtilen predicate tarafından tanımlanan koşulları sağlayıp sağlamadığını belirler.
type: docs
weight: 677
url: /tr/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodu

Belirtilen dizideki tüm elemanların, belirtilen predicate tarafından tanımlanan koşulları sağlayıp sağlamadığını belirler.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) öğeleri, koşullara karşı eşleştirilecek |
| match | [System::Predicate](../../predicate/)\<T\> | Dizi elemanlarını eşleştirmek için koşulları tanımlayan bir predicate |

### Dönüş Değeri

true if all elements of the array arr satisfy the conditions defined by predicate match, otherwise false

## Diğer Bağlantılar

* Tip Tanımı [ArrayPtr](../../arrayptr/)
* Tip Tanımı [Predicate](../../predicate/)
* Sınıf [Array](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)