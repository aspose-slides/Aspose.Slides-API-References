---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API Reference
description: Checks if both type arguments are arrays or lists. If so, value member is set to true, otherwise it is set to false.
type: docs
weight: 131
url: /cpp/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Checks if both type arguments are arrays or lists. If so, value member is set to true, otherwise it is set to false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)
