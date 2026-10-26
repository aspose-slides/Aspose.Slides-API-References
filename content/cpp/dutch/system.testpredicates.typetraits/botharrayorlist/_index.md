---
title: BothArrayOrList
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of beide type argumenten arrays of lijsten zijn. Zo ja, wordt het value lid ingesteld op true, anders op false.
type: docs
weight: 131
url: /nl/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Controleert of beide type argumenten arrays of lijsten zijn. Zo ja, wordt het value lid ingesteld op true, anders op false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Zie ook

* Naamruimte [System::TestPredicates::TypeTraits](../)
* Bibliotheek [Aspose.Slides](../../)