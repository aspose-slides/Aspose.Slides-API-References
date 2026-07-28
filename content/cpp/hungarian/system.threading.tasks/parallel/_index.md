---
title: Parallel
second_title: Aspose.Slides for C++ API referencia
description: Támogatást nyújt párhuzamos ciklusok és régiók számára.
type: docs
weight: 1
url: /hu/system.threading.tasks/parallel/
---
## Parallel osztály

Támogatást nyújt párhuzamos ciklusok és régiók számára.

```cpp
class Parallel
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Végrehajt egy foreach műveletet egy IEnumerable-ön, amelyben az iterációk párhuzamosan futtathatók. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Végrehajt egy foreach műveletet egy IEnumerable-ön, amelyben az iterációk párhuzamosan futtathatók. |

## Megjegyzések

Ez az osztály metódusokat biztosít a ciklusok és műveletek párhuzamos végrehajtásához.

## Lásd még

* Névtere [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)