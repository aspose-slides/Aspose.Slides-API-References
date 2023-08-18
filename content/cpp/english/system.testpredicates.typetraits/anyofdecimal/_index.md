---
title: AnyOfDecimal
second_title: Aspose.Slides for C++ API Reference
description: "Checks that at least one of type arguments is System::Decimal. If so, sets value member to true, otherwise it is false."
type: docs
weight: 92
url: /system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Checks that at least one of type arguments is [System::Decimal](../../system/decimal/). If so, sets value member to true, otherwise it is false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)