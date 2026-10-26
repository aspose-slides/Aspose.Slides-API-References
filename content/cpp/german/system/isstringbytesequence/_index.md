---
title: IsStringByteSequence
second_title: Aspose.Slides für C++ API-Referenz
description: Template-Magie, um zu überprüfen, ob ein Typ eine Sequenz von Zeichenkettenzeichen ist.
type: docs
weight: 1717
url: /de/system/isstringbytesequence/
---
## IsStringByteSequence Struktur

Template-Magie, um zu überprüfen, ob ein Typ eine Sequenz von Zeichenkettenzeichen ist.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | geprüfter Typ. |
| CharT | Zeichentyp, gegen den geprüft wird. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)