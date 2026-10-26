---
title: AnyOfDecimal
second_title: Aspose.Slides pro C++ API Reference
description: "Kontroluje, zda alespoň jeden z typových argumentů je System::Decimal. Pokud ano, nastaví člen value na true, jinak je false."
type: docs
weight: 92
url: /cs/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Kontroluje, zda alespoň jeden z typových argumentů je [System::Decimal](../../system/decimal/). Pokud ano, nastaví člen value na true, jinak je false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Viz také

* jmenný prostor [System::TestPredicates::TypeTraits](../)
* Knihovna [Aspose.Slides](../../)