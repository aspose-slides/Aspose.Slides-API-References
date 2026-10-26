---
title: HasFlag()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die angegebenen Bits in einer bitweisen Darstellung des angegebenen enum-Werts gesetzt sind.
type: docs
weight: 14
url: /de/system/enum/hasflag/
---
## Enum::HasFlag(E, E) Methode


Bestimmt, ob die angegebenen Bits in einer bitweisen Darstellung des angegebenen enum-Werts gesetzt sind.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | E | Der zu testende enum-Wert |
| mask | E | Die Maske, gegen die die Bits des Wertes geprüft werden |

### Rückgabewert

true, wenn die in **mask** gesetzten Bits auch in **value** gesetzt sind, andernfalls – false

## Siehe auch

* Struct [Enum](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)