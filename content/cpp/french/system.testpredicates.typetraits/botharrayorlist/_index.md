---
title: BothArrayOrList
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si les deux arguments de type sont des tableaux ou des listes. Si c’est le cas, le membre value est défini sur true, sinon il est défini sur false.
type: docs
weight: 131
url: /fr/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Vérifie si les deux arguments de type sont des tableaux ou des listes. Si c’est le cas, le membre value est défini sur true, sinon il est défini sur false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Voir également

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)