---
title: AreFPandArithmetic
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar att T1 är aritmetisk och T2 är flyttal, eller tvärtom. Om så är fallet sätts value-medlemmen till true, annars är den false.
type: docs
weight: 79
url: /sv/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Kontrollerar att **T1** är aritmetisk och **T2** är flyttal, eller tvärtom. Om så är fallet sätts value-medlemmen till true, annars är den false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Se även

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)