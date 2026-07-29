---
title: MakeYieldEnumerator()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en IEnumerator från en yield-funktion.
type: docs
weight: 2432
url: /sv/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function


Skapar en IEnumerator från en yield-funktion.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i sekvensen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Yield-funktionen som ska köras |

### Returvärde

Delad pekare till IEnumerator

## Se också

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)