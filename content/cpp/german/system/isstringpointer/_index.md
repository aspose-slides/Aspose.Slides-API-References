---
title: IsStringPointer
second_title: Aspose.Slides für C++ API Referenz
description: Template-Magie, um zu prüfen, ob ein Typ ein Zeiger auf eine Zeichenkette ist.
type: docs
weight: 1743
url: /de/system/isstringpointer/
---
## IsStringPointer struct

Template-Magie, um zu prüfen, ob ein Typ ein Zeiger auf eine Zeichenkette ist.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | überprüfter Typ. |
| CharT | Zeichentyp, gegen den geprüft wird. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)