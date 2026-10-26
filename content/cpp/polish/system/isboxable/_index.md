---
title: IsBoxable
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Predykat szablonu, który sprawdza, czy opakowywanie określonego typu jest obsługiwane.
type: docs
weight: 1665
url: /pl/system/isboxable/
---
## IsBoxable struct

Predykat szablonu, który sprawdza, czy opakowywanie określonego typu jest obsługiwane.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ do sprawdzenia |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)