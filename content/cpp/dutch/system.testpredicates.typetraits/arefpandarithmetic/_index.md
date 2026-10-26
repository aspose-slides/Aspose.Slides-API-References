---
title: AreFPandArithmetic
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of T1 rekenkundig is en T2 een floating point is, of omgekeerd. Zo ja, wordt value member op true gezet, anders is deze false.
type: docs
weight: 79
url: /nl/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Controleert of **T1** rekenkundig is en **T2** een floating-pointtype, of omgekeerd. Zo ja, wordt de waarde-eigenschap op true gezet, anders is deze false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Zie ook

* Naamruimte [System::TestPredicates::TypeTraits](../)
* Bibliotheek [Aspose.Slides](../../)