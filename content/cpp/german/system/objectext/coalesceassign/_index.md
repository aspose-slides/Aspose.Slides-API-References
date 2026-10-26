---
title: CoalesceAssign()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementierung der Übersetzung des '??=' Operators.
type: docs
weight: 183
url: /de/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) Methode

Implementierung der Übersetzung des '??=' Operators.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T0 | LHS-Werttyp. |
| T1 | Typ des Lambda, das den RHS-Ausdruck kapselt. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T0\& | LHS-Wert. |
| func | T1 | RHS-Ausdruck. |

### Rückgabewert

Wenn der LHS-Wert nicht null ist, wird LHS zurückgegeben, andernfalls wird der RHS-Ausdruck berechnet und das Ergebnis zurückgegeben.

## Siehe auch

* Klasse [ObjectExt](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)