---
title: AreFPandArithmetic
second_title: Aspose.Slides için C++ API Referansı
description: T1'in aritmetik ve T2'nin kayan nokta olduğunu, ya da tersini kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur.
type: docs
weight: 79
url: /tr/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

**T1**'in aritmetik ve **T2**'nin kayan nokta olduğunu, ya da tersini kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## Ayrıca Bakınız

* Ad Alanı [System::TestPredicates::TypeTraits](../)
* Kütüphane [Aspose.Slides](../../)