---
title: BothArrayOrList
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda oba typové argumenty jsou pole nebo seznamy. Pokud ano, člen value je nastaven na true, jinak je nastaven na false.
type: docs
weight: 131
url: /cs/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Kontroluje, zda oba typové argumenty jsou pole nebo seznamy. Pokud ano, člen value je nastaven na true, jinak je nastaven na false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Viz také

* Jmenný prostor [System::TestPredicates::TypeTraits](../)
* Knihovna [Aspose.Slides](../../)