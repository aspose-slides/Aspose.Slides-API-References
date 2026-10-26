---
title: AreFPandArithmetic
second_title: Aspose.Slides – dokumentacja API dla C++
description: Sprawdza, czy T1 jest typem arytmetycznym, a T2 jest typem zmiennoprzecinkowym, lub odwrotnie. Jeśli tak, ustawia członek value na true, w przeciwnym razie jest false.
type: docs
weight: 79
url: /pl/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Sprawdza, czy **T1** jest arytmetyczny i **T2** jest liczbą zmiennoprzecinkową, lub odwrotnie. Jeśli tak, ustawia członek value na true, w przeciwnym razie jest false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Zobacz także

* Przestrzeń nazw [System::TestPredicates::TypeTraits](../)
* Biblioteka [Aspose.Slides](../../)