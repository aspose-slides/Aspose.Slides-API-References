---
title: AnyOfDecimal
second_title: Référence API Aspose.Slides pour C++
description: "Vérifie qu'au moins un des arguments de type est System::Decimal. Si c'est le cas, définit le membre value sur true, sinon il est false."
type: docs
weight: 92
url: /fr/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Vérifie qu'au moins un des arguments de type est [System::Decimal](../../system/decimal/). Si c'est le cas, définit le membre value sur true, sinon il est false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)