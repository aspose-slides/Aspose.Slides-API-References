---
title: MakeYieldEnumerable()
second_title: Aspose.Slides pro referenční příručku API C++
description: Vytvoří IEnumerable z funkce yield.
type: docs
weight: 2419
url: /cs/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) funkce

Vytvoří IEnumerable z funkce yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | The type of elements in the sequence |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### Návratová hodnota

Sdílený ukazatel na IEnumerable

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* třída [IEnumerable](../../system.collections.generic/ienumerable/)
* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)