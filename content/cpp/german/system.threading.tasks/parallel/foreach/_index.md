---
title: ForEach()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt eine foreach-Operation auf einem IEnumerable aus, bei der die Iterationen parallel ausgeführt werden können.
type: docs
weight: 1
url: /de/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) Methode

Führt eine foreach-Operation auf einem IEnumerable aus, bei der die Iterationen parallel ausgeführt werden können.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSource | The type of the data in the source. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | An object that configures the behavior of this operation. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Rückgabewert

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.

## Bemerkungen

Diese Methode partitioniert die Quell-Enumeration und führt den Body-Delegate gleichzeitig auf mehreren Threads aus.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) Methode

Führt eine foreach-Operation auf einem IEnumerable aus, bei der die Iterationen parallel ausgeführt werden können.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TSource | The type of the data in the source. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Rückgabewert

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.

## Bemerkungen

Verwendet das Standard-[ParallelOptions](../../paralleloptions/) mit unbegrenzter Parallelität und ohne Abbruch.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasse [ParallelLoopResult](../../parallelloopresult/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [ParallelOptions](../../paralleloptions/)
* Klasse [Parallel](../)
* Namensraum [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)