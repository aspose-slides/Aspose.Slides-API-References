---
title: MakeYieldEnumerable()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett IEnumerable från en yield-funktion.
type: docs
weight: 2419
url: /sv/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function


Skapar en IEnumerable från en yield-funktion.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i sekvensen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Yield-funktionen att köra |

### Returvärde

Delad pekare till IEnumerable

## Se också

* Typedef [SharedPtr](../sharedptr/)
* Klass [IEnumerable](../../system.collections.generic/ienumerable/)
* Namnutrymme [System](../)
* Bibliotek [Aspose.Slides](../../)