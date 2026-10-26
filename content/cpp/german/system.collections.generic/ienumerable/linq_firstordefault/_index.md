---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das erste Element einer Sequenz zurück oder einen Standardwert, wenn die Sequenz leer ist.
type: docs
weight: 66
url: /de/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() Methode

Gibt das erste Element einer Sequenz zurück oder einen Standardwert, wenn die Sequenz leer ist.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Rückgabewert

Erstes Element in der Sequenz oder ein standardmäßig konstruiertes Objekt, wenn die Sequenz leer ist.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) Methode

Gibt das erste Element der Sequenz zurück, das eine Bedingung erfüllt, oder einen Standardwert, wenn ein solches Element nicht gefunden wird.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Eine Funktion, um jedes Element auf eine Bedingung zu testen. |

### Rückgabewert

default(T), falls die Quelle leer ist oder kein Element den durch predicate angegebenen Test besteht; andernfalls das erste Element in source, das den durch predicate angegebenen Test besteht.

## Siehe auch

* Klasse [IEnumerable](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)