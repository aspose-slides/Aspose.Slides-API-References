---
title: ForEach()
second_title: Aspose.Slides for C++ API Reference
description: Executes a foreach operation on an IEnumerable in which iterations may run in parallel.
type: docs
weight: 1
url: /system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Executes a foreach operation on an IEnumerable in which iterations may run in parallel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | An object that configures the behavior of this operation. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Return Value

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Remarks



This method partitions the source enumerable and executes the body delegate on multiple threads concurrently. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Executes a foreach operation on an IEnumerable in which iterations may run in parallel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Return Value

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Remarks



Uses default [ParallelOptions](../../paralleloptions/) with unlimited parallelism and no cancellation. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [ParallelLoopResult](../../parallelloopresult/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)