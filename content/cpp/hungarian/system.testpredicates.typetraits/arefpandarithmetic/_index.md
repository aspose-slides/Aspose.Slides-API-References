---
title: AreFPandArithmetic
second_title: Aspose.Slides C++ API hivatkozás
description: Ellenőrzi, hogy a T1 aritmetikus, és a T2 lebegőpontos, vagy fordítva. Ha igen, a value tag értékét true-ra állítja, ellenkező esetben false.
type: docs
weight: 79
url: /hu/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Ellenőrzi, hogy **T1** aritmetikus, és **T2** lebegőpontos, vagy fordítva. Ha igen, a value tag értékét true-ra állítja, ellenkező esetben false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## Lásd még

* Névtér [System::TestPredicates::TypeTraits](../)
* Könyvtár [Aspose.Slides](../../)