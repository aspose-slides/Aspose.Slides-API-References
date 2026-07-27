---
title: AreFPandArithmetic
second_title: Aspose.Slides para la referencia de la API de C++
description: Comprueba que T1 sea aritmético y T2 sea de punto flotante, o viceversa. En ese caso, establece el miembro value a true, de lo contrario es false.
type: docs
weight: 79
url: /es/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Comprueba que **T1** sea aritmético y **T2** sea de punto flotante, o viceversa. En ese caso, establece el miembro value a true, de lo contrario es false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Ver también

* Espacio de nombres [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)