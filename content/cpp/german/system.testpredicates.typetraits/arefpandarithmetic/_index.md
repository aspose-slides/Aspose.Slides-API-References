---
title: AreFPandArithmetic
second_title: Aspose.Slides für C++ API-Referenz
description: Prüft, ob T1 arithmetisch und T2 Fließkomma ist, oder umgekehrt. Falls ja, wird das value-Mitglied auf true gesetzt, andernfalls ist es false.
type: docs
weight: 79
url: /de/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Prüft, ob **T1** arithmetisch und **T2** Fließkomma ist, oder umgekehrt. Falls ja, wird das value-Member auf true gesetzt, andernfalls ist es false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Siehe Auch

* Namensraum [System::TestPredicates::TypeTraits](../)
* Bibliothek [Aspose.Slides](../../)