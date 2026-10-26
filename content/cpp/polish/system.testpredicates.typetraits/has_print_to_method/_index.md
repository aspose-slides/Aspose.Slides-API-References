---
title: has_print_to_method
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Sprawdza przeciążenie funkcji PrintTo, które przyjmuje podany typ jako pierwszy argument. Jeśli przeciążenie istnieje, dziedziczy po std::true_type, w przeciwnym razie dziedziczy po std::false_type."
type: docs
weight: 27
url: /pl/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Sprawdza przeciążenie funkcji PrintTo, które przyjmuje podany typ jako pierwszy argument. Jeśli przeciążenie istnieje, dziedziczy po std::true_type, w przeciwnym razie dziedziczy po std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ do sprawdzenia. |
| Enable | Formalny argument pozwalający na działanie SFINAE. |

## Zobacz także

* Przestrzeń nazw [System::TestPredicates::TypeTraits](../)
* Biblioteka [Aspose.Slides](../../)