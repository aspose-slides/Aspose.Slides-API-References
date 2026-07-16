---
title: AreFPandArithmetic
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie que T1 est arithmétique et que T2 est un point flottant, ou inversement. Si c’est le cas, le membre value est mis à true, sinon il est false.
type: docs
weight: 79
url: /fr/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

Vérifie que **T1** est arithmétique et **T2** est un point flottant, ou inversement. Si c’est le cas, le membre value est mis à true, sinon il est false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)