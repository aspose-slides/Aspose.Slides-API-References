---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API Referansı
description: Her iki tür argümanı da dizi veya liste mi diye kontrol eder. Eğer öyleyse value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır.
type: docs
weight: 131
url: /tr/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Her iki tür argümanı da dizi veya liste mi diye kontrol eder. Eğer öyleyse value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Ayrıca Bakınız

* Ad Alanı [System::TestPredicates::TypeTraits](../)
* Kütüphane [Aspose.Slides](../../)