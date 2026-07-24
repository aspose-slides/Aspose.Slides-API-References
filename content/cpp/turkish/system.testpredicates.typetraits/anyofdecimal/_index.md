---
title: AnyOfDecimal
second_title: Aspose.Slides için C++ API Referansı
description: "Tip argümanlarından en az birinin System::Decimal olduğunu kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur."
type: docs
weight: 92
url: /tr/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Tip argümanlarından en az birinin [System::Decimal](../../system/decimal/) olduğunu kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Diğer Bağlantılar

* Namespace [System::TestPredicates::TypeTraits](../)
* Kütüphane [Aspose.Slides](../../)