---
title: TryGetLast()
second_title: Aspose.Slides für C++ API Referenz
description: Versucht, das letzte Element der Sammlung zu erhalten.
type: docs
weight: 261
url: /de/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) Funktion

Versucht, das letzte Element der Sammlung zu erhalten.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente der Sammlung. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Die Sammlung, aus der ein Element zu erhalten ist. |
| found | **bool**\& | Der Ausgabeparameter. Gibt true zurück, wenn die Sammlung irgendein Element enthält. Andernfalls wird false zurückgegeben. |

### Rückgabewert

Gibt das letzte Element der Sammlung zurück. Der Standardwert des Typs wird zurückgegeben, wenn die Sammlung leer ist.

## Siehe auch

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)