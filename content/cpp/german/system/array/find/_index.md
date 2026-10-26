---
title: Find()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchsucht das angegebene Array nach dem ersten Element, das die Bedingungen des angegebenen Prädikats erfüllt.
type: docs
weight: 651
url: /de/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) method


Durchsucht das angegebene Array nach dem ersten Element, das die Bedingungen des angegebenen Prädikats erfüllt.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) zum Durchsuchen eines Elements in |
| match | [System::Predicate](../../predicate/)\<T\> | Ein Prädikat, das die Bedingungen definiert, nach denen Array-Elemente abgeglichen werden |

### Rückgabewert

Kopie des ersten Elements im Array, das die durch das Prädikat definierten Bedingungen erfüllt, andernfalls der Standardwert des Typs T

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)