---
title: IsStringByteSequence
second_title: Aspose.Slides för C++ API-referens
description: Mallmagi för att kontrollera om en typ är en sekvens av teckensträngar.
type: docs
weight: 1717
url: /sv/system/isstringbytesequence/
---
## IsStringByteSequence struct


Mallmagi för att kontrollera om en typ är en sekvens av teckensträngar.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | kontrollerad typ. |
| CharT | Teckentyp att jämföra med. |

## Se även

* Namnutrymd [System](../)
* Bibliotek [Aspose.Slides](../../)