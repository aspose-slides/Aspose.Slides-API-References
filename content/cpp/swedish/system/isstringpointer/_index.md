---
title: IsStringPointer
second_title: Aspose.Slides för C++ API-referens
description: Mallmagik för att kontrollera om en typ är en pekare till en teckensträng.
type: docs
weight: 1743
url: /sv/system/isstringpointer/
---
## IsStringPointer struct


Mallmagik för att kontrollera om en typ är en pekare till en teckensträng.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Templateparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | kontrollerad typ. |
| CharT | Teckentyp att kontrollera mot. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)