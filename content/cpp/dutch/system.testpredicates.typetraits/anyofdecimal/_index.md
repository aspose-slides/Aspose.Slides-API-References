---
title: AnyOfDecimal
second_title: Aspose.Slides voor C++ API-referentie
description: "Controleert of ten minste één van de type-argumenten System::Decimal is. Zo ja, wordt het value member op true gezet, anders is het false."
type: docs
weight: 92
url: /nl/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Controleert of ten minste één van de type-argumenten [System::Decimal](../../system/decimal/) is. Zo ja, wordt het value member op true gezet, anders is het false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Zie ook

* Naamruimte [System::TestPredicates::TypeTraits](../)
* Bibliotheek [Aspose.Slides](../../)