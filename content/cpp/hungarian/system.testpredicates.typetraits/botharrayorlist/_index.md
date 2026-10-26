---
title: BothArrayOrList
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a két típusargumentum tömb vagy lista-e. Ha igen, a value tag értéke true, egyébként false.
type: docs
weight: 131
url: /hu/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Ellenőrzi, hogy a két típusargumentum tömb vagy lista-e. Ha igen, a value tag értéke true, egyébként false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Lásd még

* Névtér [System::TestPredicates::TypeTraits](../)
* Könyvtár [Aspose.Slides](../../)