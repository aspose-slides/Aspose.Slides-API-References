---
title: AreFPandArithmetic
second_title: Aspose.Slides per il riferimento API C++
description: Verifica che T1 sia aritmetico e T2 sia a virgola mobile, oppure viceversa. In tal caso, imposta il membro value su true, altrimenti è false.
type: docs
weight: 79
url: /it/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Verifica che **T1** sia aritmetico e **T2** sia a virgola mobile, oppure viceversa. In tal caso, imposta il membro value su true, altrimenti è false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Vedi anche

* Spazio dei nomi [System::TestPredicates::TypeTraits](../)
* Libreria [Aspose.Slides](../../)