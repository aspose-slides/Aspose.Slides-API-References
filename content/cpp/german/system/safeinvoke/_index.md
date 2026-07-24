---
title: SafeInvoke()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementierung der Übersetzung des '?.'-Operators.
type: docs
weight: 2653
url: /de/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) Funktion

Implementierung der Übersetzung des '?.'-Operators.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T0 | expression type. |
| T1 | Type of lambda encapsulating 'WhenTrue' expression. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | T0\&& | expression value. |
| func | T1\&& | 'WhenTrue' expression bound to functor. |

### Rückgabewert

Wenn expr value nicht null ist, wird func mit seinem Wert als erstem Argument aufgerufen, andernfalls wird null zurückgegeben.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)