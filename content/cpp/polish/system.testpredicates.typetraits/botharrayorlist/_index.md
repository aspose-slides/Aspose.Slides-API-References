---
title: BothArrayOrList
second_title: Aspose.Slides dla C++ - referencja API
description: Sprawdza, czy oba argumenty typu są tablicami lub listami. Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false.
type: docs
weight: 131
url: /pl/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Sprawdza, czy oba argumenty typu są tablicami lub listami. Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Zobacz także

* Przestrzeń nazw [System::TestPredicates::TypeTraits](../)
* Biblioteka [Aspose.Slides](../../)