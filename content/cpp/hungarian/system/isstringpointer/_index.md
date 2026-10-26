---
title: IsStringPointer
second_title: Aspose.Slides for C++ API Referenciája
description: Sablonvarázslat annak ellenőrzésére, hogy egy típus karakterlánc mutatója-e.
type: docs
weight: 1743
url: /hu/system/isstringpointer/
---
## IsStringPointer struktúra

Sablonvarázslat annak ellenőrzésére, hogy egy típus karakterlánc mutatója-e.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | ellenőrzött típus. |
| CharT | karaktertípus, amely ellenőrizendő. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)