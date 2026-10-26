---
title: Parallel
second_title: Aspose.Slides dla referencji API C++
description: Zapewnia obsługę pętli równoległych i regionów.
type: docs
weight: 1
url: /pl/system.threading.tasks/parallel/
---
## Klasa Parallel


Zapewnia obsługę pętli równoległych i regionów.

```cpp
class Parallel
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Wykonuje operację foreach na IEnumerable, w której iteracje mogą być wykonywane równolegle. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Wykonuje operację foreach na IEnumerable, w której iteracje mogą być wykonywane równolegle. |
## Uwagi


Ta klasa udostępnia metody do równoległego wykonywania pętli i operacji. 
## Zobacz także

* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)