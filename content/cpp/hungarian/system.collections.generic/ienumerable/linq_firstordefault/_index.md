---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres.
type: docs
weight: 66
url: /hu/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metódus


Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Visszatérési érték

Az első elem a sorozatban, vagy alapértelmezett konstrukcióval létrehozott érték, ha a sorozat üres.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metódus


Visszaadja a sorozat első olyan elemét, amely megfelel egy feltételnek, vagy egy alapértelmezett értéket, ha nem talál ilyen elemet.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Egy függvény, amely minden elemet egy feltétel alapján tesztel. |

### Visszatérési érték

default(T), ha a forrás üres, vagy ha egy elem sem teljesíti a predicate által megadott tesztet; egyébként a forrás első olyan eleme, amely megfelel a predicate által meghatározott tesztnek.

## Lásd még

* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)