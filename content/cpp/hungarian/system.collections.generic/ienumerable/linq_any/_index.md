---
title: LINQ_Any()
second_title: Aspose.Slides C++ API referenciája
description: Megállapítja, hogy egy sorozat tartalmaz-e elemeket.
type: docs
weight: 157
url: /hu/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() metódus

Megállapítja, hogy egy sorozat tartalmaz-e elemeket.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### Visszatérési érték

true ha a forrás sorozat tartalmaz elemeket; egyébként false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) metódus

Megállapítja, hogy egy sorozat bármely eleme létezik-e vagy megfelel-e egy feltételnek.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Egy függvény, amely minden elemet egy feltétel szerint tesztel. |

### Visszatérési érték

true ha a forrás sorozat tartalmaz elemeket; egyébként false.

## Lásd még

* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)