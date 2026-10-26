---
title: MakeYieldEnumerator()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří IEnumerator z yield funkce.
type: docs
weight: 2432
url: /cs/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) funkce

Vytvoří IEnumerator z yield funkce.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v sekvenci |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Yield funkce k provedení |

### Návratová hodnota

Sdílený ukazatel na IEnumerator

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Třída [IEnumerator](../../system.collections.generic/ienumerator/)
* Obor názvů [System](../)
* Knihovna [Aspose.Slides](../../)