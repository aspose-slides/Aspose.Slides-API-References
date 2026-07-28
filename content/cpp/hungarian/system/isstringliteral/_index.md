---
title: IsStringLiteral
second_title: Aspose.Slides C++ API referencia
description: Sablontrükk a típus karakterlánc literálként való ellenőrzéséhez.
type: docs
weight: 1730
url: /hu/system/isstringliteral/
---
## IsStringLiteral struct

Sablontrükk, amely ellenőrzi, hogy egy típus karakterlánc literál-e.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | ellenőrzött típus. |
| CharT | Karaktertípus, amivel ellenőrizni kell. |

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)