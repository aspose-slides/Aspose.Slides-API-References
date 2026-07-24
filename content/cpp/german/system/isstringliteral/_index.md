---
title: IsStringLiteral
second_title: Aspose.Slides für C++ API Referenz
description: Template-Magie, um zu prüfen, ob ein Typ ein String-Literal ist.
type: docs
weight: 1730
url: /de/system/isstringliteral/
---
## IsStringLiteral struct

Template-Magie, um zu prüfen, ob ein Typ ein String-Literal ist.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | geprüfter Typ. |
| CharT | Zeichentyp, gegen den geprüft wird. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)