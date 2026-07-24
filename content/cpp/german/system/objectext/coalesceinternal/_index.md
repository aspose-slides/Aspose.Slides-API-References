---
title: CoalesceInternal()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementierung der Übersetzung des '??'-Operators für nicht nullable Typen. Überladung für den Fall, dass RT2 in RT1 konvertierbar ist.
type: docs
weight: 157
url: /de/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) Methode

Implementierung der Übersetzung des '??'-Operators für nicht nullable Typen. Überladung für den Fall, dass RT2 in RT1 konvertierbar ist.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T0 | LHS Werttyp. |
| T1 | Typ des Lambdas, das den RHS-Ausdruck kapselt. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | RT1 | LHS Wert. |
| func | F | RHS Ausdruck. |

### Rückgabewert

Wenn der LHS-Wert nicht null ist, wird LHS zurückgegeben, andernfalls wird der RHS-Ausdruck berechnet und das Ergebnis zurückgegeben.

## Siehe auch

* Klasse [ObjectExt](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)