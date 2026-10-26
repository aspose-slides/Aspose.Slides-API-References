---
title: operator|=()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Stosuje operator|=() do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie.
type: docs
weight: 261
url: /pl/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) metoda


Zastosowuje [operator|=()](./) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Parametr szablonu umożliwiający działanie SFINAE. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | **bool** | Wartość logiczna używana jako wartość po prawej stronie [operator|=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Wartość zwracana

Referencja do siebie.

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)