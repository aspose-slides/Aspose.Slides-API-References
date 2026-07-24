---
title: RoundImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist.
type: docs
weight: 287
url: /de/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie die Rundung durchgeführt wird, wenn **value** gleich weit von zwei nächsten Zahlen entfernt ist. |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl an Stellen, die **value** am nächsten liegt.

## Siehe auch

* Aufzählung [MidpointRounding](../../midpointrounding/)
* Struktur [MathF](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)