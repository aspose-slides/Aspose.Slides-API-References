---
title: AnyOfDecimal
second_title: Aspose.Slides für C++ API-Referenz
description: "Überprüft, ob mindestens ein Typargument System::Decimal ist. Falls ja, wird das value-Mitglied auf true gesetzt, andernfalls ist es false."
type: docs
weight: 92
url: /de/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Überprüft, ob mindestens ein Typargument [System::Decimal](../../system/decimal/) ist. Falls ja, wird das value-Mitglied auf true gesetzt, andernfalls ist es false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Siehe auch

* Namensraum [System::TestPredicates::TypeTraits](../)
* Bibliothek [Aspose.Slides](../../)