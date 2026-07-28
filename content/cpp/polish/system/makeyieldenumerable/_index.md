---
title: MakeYieldEnumerable()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy IEnumerable z funkcji yield.
type: docs
weight: 2419
url: /pl/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) funkcja

Tworzy IEnumerable z funkcją yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w sekwencji |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Funkcja yield do wykonania |

### Wartość zwracana

Wskaźnik współdzielony do IEnumerable

## Zobacz także

* Definicja typu [SharedPtr](../sharedptr/)
* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)