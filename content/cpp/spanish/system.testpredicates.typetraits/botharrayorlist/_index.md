---
title: BothArrayOrList
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si ambos argumentos de tipo son arrays o listas. Si es así, el miembro value se establece en true, de lo contrario se establece en false.
type: docs
weight: 131
url: /es/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Comprueba si ambos argumentos de tipo son arrays o listas. Si es así, el miembro value se establece en true, de lo contrario se establece en false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Ver también

* Espacio de nombres [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)