---
title: TryGetFirst()
second_title: Aspose.Slides für C++ API-Referenz
description: Versucht, das erste Element der Sammlung zu erhalten.
type: docs
weight: 248
url: /de/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) Funktion

Versucht, das erste Element der Sammlung zu erhalten.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente der Sammlung. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Die Sammlung, aus der ein Element erworben werden soll. |
| found | **bool**\& | Der Ausgabewertparameter. Gibt true zurück, wenn die Sammlung irgendein Element enthält. Andernfalls wird false zurückgegeben. |

### Rückgabewert

Gibt das erste Element der Sammlung zurück. Der Standardwert des Typs wird zurückgegeben, wenn die Sammlung leer ist.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) Funktion

Versucht, das erste Element der Sammlung zu erhalten, das die Prädikatfunktion erfüllt.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente der Sammlung. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Die Sammlung, aus der ein Element erworben werden soll. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Die Prädikatfunktion. |
| found | **bool**\& | Der Ausgabewertparameter. Gibt true zurück, wenn die Sammlung irgendein Element enthält. Andernfalls wird false zurückgegeben. |

### Rückgabewert

Gibt das erste Element der Sammlung zurück. Der Standardwert des Typs wird zurückgegeben, wenn kein Element gefunden wird, das die angegebene Prädikatfunktion erfüllt.

## Siehe auch

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Klasse [Func](../../system/func/)
* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)