---
title: Parallel
second_title: Aspose.Slides pro C++ API referenci
description: Poskytuje podporu pro paralelní smyčky a oblasti.
type: docs
weight: 1
url: /cs/system.threading.tasks/parallel/
---
## Parallel třída

Poskytuje podporu pro paralelní smyčky a oblasti.

```cpp
class Parallel
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Provede operaci foreach na IEnumerable, ve které mohou být iterace spuštěny paralelně. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Provede operaci foreach na IEnumerable, ve které mohou být iterace spuštěny paralelně. |

## Poznámky

Tato třída poskytuje metody pro paralelní provádění smyček a operací.

## Viz také

* Namespace [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)