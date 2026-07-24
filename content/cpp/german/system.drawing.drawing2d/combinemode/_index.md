---
title: CombineMode
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie Clipping-Regionen kombiniert werden.
type: docs
weight: 170
url: /de/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Gibt an, wie Clipping-Regionen kombiniert werden.

```cpp
enum class CombineMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Replace | 0 | Eine Clipping-Region wird durch eine andere ersetzt. |
| Intersect | 1 | Die beiden Clipping-Regionen werden durch Bilden ihrer Schnittmenge kombiniert. |
| Union | 2 | Die beiden Clipping-Regionen werden durch Bilden ihrer Vereinigung kombiniert. |
| Xor | 3 | Die beiden Clipping-Regionen werden kombiniert, indem nur der Bereich genommen wird, der von einer der beiden Regionen eingeschlossen ist, jedoch nicht von beiden. |
| Exclude | 4 | Zwei Clipping-Regionen werden kombiniert, indem der Bereich der ersten Region genommen wird, der nicht mit der zweiten überlappt. |
| Complement | 5 | Zwei Clipping-Regionen werden kombiniert, indem der Bereich der zweiten Region genommen wird, der nicht mit der ersten überlappt. |

## Siehe auch

* Namensraum [System::Drawing::Drawing2D](../)
* Bibliothek [Aspose.Slides](../../)