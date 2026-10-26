---
title: IsStringByteSequence
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Magia szablonowa sprawdzająca, czy typ jest sekwencją znaków ciągu.
type: docs
weight: 1717
url: /pl/system/isstringbytesequence/
---
## IsStringByteSequence struktura

Magia szablonowa sprawdzająca, czy typ jest sekwencją znaków ciągu.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | sprawdzany typ. |
| CharT | Typ znaku do sprawdzenia. |

## Zobacz również

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)