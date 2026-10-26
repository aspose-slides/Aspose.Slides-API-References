---
title: IsStringPointer
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Magia szablonu sprawdzająca, czy typ jest wskaźnikiem na ciąg znaków.
type: docs
weight: 1743
url: /pl/system/isstringpointer/
---
## IsStringPointer struktura

Magia szablonu sprawdzająca, czy typ jest wskaźnikiem na ciąg znaków.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | sprawdzany typ. |
| CharT | Typ znaku, z którym sprawdzany jest. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)