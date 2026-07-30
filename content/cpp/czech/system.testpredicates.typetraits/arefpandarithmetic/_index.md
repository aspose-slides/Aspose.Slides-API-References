---
title: AreFPandArithmetic
second_title: Aspose.Slides pro C++ referenční příručka API
description: Kontroluje, že T1 je aritmetický a T2 je s plovoucí desetinnou čárkou, nebo naopak. Pokud ano, nastaví člen value na true, jinak je false.
type: docs
weight: 79
url: /cs/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

Kontroluje, že **T1** je aritmetický a **T2** je s plovoucí desetinnou čárkou, nebo naopak. Pokud ano, nastaví člen value na true, jinak je false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## Viz také

* Jmenný prostor [System::TestPredicates::TypeTraits](../)
* Knihovna [Aspose.Slides](../../)