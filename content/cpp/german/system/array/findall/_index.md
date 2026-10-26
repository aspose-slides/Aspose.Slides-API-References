---
title: FindAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft alle Elemente ab, die den Bedingungen entsprechen, die durch das angegebene Prädikat definiert sind.
type: docs
weight: 664
url: /de/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) Methode

Ruft alle Elemente ab, die den vom angegebenen Prädikat definierten Bedingungen entsprechen.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) zum Suchen von Elementen in |
| match | [System::Predicate](../../predicate/)\<T\> | Ein Prädikat, das die Bedingungen definiert, denen Array-Elemente entsprechen sollen |

### Rückgabewert

Ein [Array](../) enthält alle Elemente, die den vom angegebenen Prädikat definierten Bedingungen entsprechen, falls gefunden; andernfalls ein leeres [Array](../).

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)