---
title: IsStringLiteral
second_title: Aspose.Slides dla C++ – referencja API
description: Magia szablonu umożliwiająca sprawdzenie, czy typ jest literałem łańcucha znaków.
type: docs
weight: 1730
url: /pl/system/isstringliteral/
---
## IsStringLiteral struct

Template magic to check if a type is a string literal.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | sprawdzany typ. |
| CharT | Typ znaku, względem którego sprawdzany jest typ. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)