---
title: FindIndex()
second_title: Aspose.Slides für C++ API-Referenz
description: Sucht das erste Element im angegebenen Array, das die Bedingungen des angegebenen Prädikats erfüllt.
type: docs
weight: 638
url: /de/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) Methode

Sucht das erste Element im angegebenen Array, das die Bedingungen des angegebenen Prädikats erfüllt.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) zum Suchen eines Elements in |
| match | [System::Predicate](../../predicate/)\<T\> | Ein Prädikat, das die Bedingungen definiert, um Array-Elemente abzugleichen |

### Rückgabewert

Der Index des ersten Elements im Array, das die durch das Prädikat definierten Bedingungen erfüllt, sonst -1

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)