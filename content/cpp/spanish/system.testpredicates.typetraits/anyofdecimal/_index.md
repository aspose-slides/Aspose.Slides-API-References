---
title: AnyOfDecimal
second_title: Referencia de API de Aspose.Slides para C++
description: "Comprueba que al menos uno de los argumentos de tipo sea System::Decimal. Si es así, establece el miembro value en true, de lo contrario es false."
type: docs
weight: 92
url: /es/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Comprueba que al menos uno de los argumentos de tipo sea [System::Decimal](../../system/decimal/). Si es así, establece el miembro value en true, de lo contrario es false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Ver también

* Espacio de nombres [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)