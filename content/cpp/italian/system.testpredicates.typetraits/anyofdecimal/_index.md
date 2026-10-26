---
title: AnyOfDecimal
second_title: Riferimento API Aspose.Slides per C++
description: "Verifica che almeno uno degli argomenti di tipo sia System::Decimal. In tal caso, imposta il membro value su true, altrimenti è false."
type: docs
weight: 92
url: /it/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Verifica che almeno uno degli argomenti di tipo sia [System::Decimal](../../system/decimal/). In tal caso, imposta il membro value su true, altrimenti è false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Vedi anche

* Spazio dei nomi [System::TestPredicates::TypeTraits](../)
* Libreria [Aspose.Slides](../../)