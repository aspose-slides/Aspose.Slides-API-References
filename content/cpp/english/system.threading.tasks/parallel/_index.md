---
title: Parallel
second_title: Aspose.Slides for C++ API Reference
description: Provides support for parallel loops and regions.
type: docs
weight: 1
url: /system.threading.tasks/parallel/
---
## Parallel class


Provides support for parallel loops and regions.

```cpp
class Parallel
```

## Methods

| Method | Description |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executes a foreach operation on an IEnumerable in which iterations may run in parallel. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executes a foreach operation on an IEnumerable in which iterations may run in parallel. |
## Remarks


This class provides methods for parallel execution of loops and operations. 
## See Also

* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)