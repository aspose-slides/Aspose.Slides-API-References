---
title: Exists()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob das angegebene Array-Objekt ein Element enthält, das die Anforderungen des angegebenen Prädikats erfüllt.
type: docs
weight: 781
url: /de/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) Methode

Bestimmt, ob das angegebene [Array](../)-Objekt ein Element enthält, das die Anforderungen des angegebenen Prädikats erfüllt.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Das Array, in dem nach dem Element gesucht werden soll |
| match | std::function\<**bool**(T)> | Funktionsobjekt, das die Anforderungen definiert und prüft, ob ein Element diese erfüllt |

### Rückgabewert

Wahr, wenn **arr** ein Element enthält, das die durch **match** definierten Anforderungen erfüllt

## Siehe auch

* Typdefinition [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)