---
title: IsStringLiteral
second_title: Aspose.Slides för C++ API-referens
description: Mallmagik för att kontrollera om en typ är en strängliteral.
type: docs
weight: 1730
url: /sv/system/isstringliteral/
---
## IsStringLiteral struktur

Mallmagik för att kontrollera om en typ är en strängliteral.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | kontrollerad typ. |
| CharT | teckentyp att kontrollera emot. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)