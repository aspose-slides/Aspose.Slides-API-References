---
title: operator&=()
second_title: Aspose.Slides dla C++ - Referencja API
description: Stosuje operator&=() do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie.
type: docs
weight: 274
url: /pl/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metoda


Zastosowuje [operator&=()](./) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Parametr szablonu, aby umożliwić działanie SFINAE. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | **bool** | Wartość logiczna używana jako wartość po prawej stronie [operator&=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Wartość zwracana

Odwołanie do siebie.

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)