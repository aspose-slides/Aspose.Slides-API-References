---
title: BothArrayOrList
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob beide Typargumente Arrays oder Listen sind. Wenn ja, wird das value member auf true gesetzt, andernfalls auf false.
type: docs
weight: 131
url: /de/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Überprüft, ob beide Typargumente Arrays oder Listen sind. Wenn ja, wird das value member auf true gesetzt, andernfalls auf false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Siehe auch

* Namensraum [System::TestPredicates::TypeTraits](../)
* Bibliothek [Aspose.Slides](../../)