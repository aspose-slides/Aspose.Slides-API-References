---
title: MakeYieldEnumerator()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy IEnumerator z funkcji yield.
type: docs
weight: 2432
url: /pl/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) funkcja


Tworzy IEnumerator z funkcji yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ elementów w sekwencji |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Funkcja yield do wykonania |

### Wartość zwracana

Współdzielony wskaźnik do IEnumerator

## Zobacz także

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)