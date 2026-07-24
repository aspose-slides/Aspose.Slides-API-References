---
title: TrueForAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob alle Elemente im angegebenen Array die durch das angegebene Prädikat definierten Bedingungen erfüllen.
type: docs
weight: 677
url: /de/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) Methode

Bestimmt, ob alle Elemente im angegebenen Array die durch das angegebene Prädikat definierten Bedingungen erfüllen.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) Elemente, die gegen die Bedingungen abgeglichen werden sollen |
| match | [System::Predicate](../../predicate/)\<T\> | Ein Prädikat, das die Bedingungen definiert, gegen die die Array-Elemente abgeglichen werden |

### Rückgabewert

true, wenn alle Elemente des Arrays arr die durch das Prädikat match definierten Bedingungen erfüllen, andernfalls false

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)