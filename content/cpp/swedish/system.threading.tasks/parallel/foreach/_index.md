---
title: ForEach()
second_title: Aspose.Slides för C++ API-referens
description: Utför en foreach-operation på en IEnumerable där iterationer kan köras parallellt.
type: docs
weight: 1
url: /sv/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) metod


Utför en foreach-operation på en IEnumerable där iterationer kan köras parallellt.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSource | Typen av data i källan. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | En enumererbar datakälla. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Ett objekt som konfigurerar beteendet för denna operation. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegaten som anropas en gång per iteration. |

### Returvärde

En [ParallelLoopResult](../../parallelloopresult/) struktur som innehåller information om vilken del av loopen som slutfördes.
## Anmärkningar



Denna metod partitionerar den källenumererbara och utför kroppdelegaten på flera trådar samtidigt. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) metod


Utför en foreach-operation på en IEnumerable där iterationer kan köras parallellt.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TSource | Typen av data i källan. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | En enumererbar datakälla. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegaten som anropas en gång per iteration. |

### Returvärde

En [ParallelLoopResult](../../parallelloopresult/) struktur som innehåller information om vilken del av loopen som slutfördes.
## Anmärkningar



Använder standard [ParallelOptions](../../paralleloptions/) med obegränsad parallellism och utan avbokning. 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klass [ParallelLoopResult](../../parallelloopresult/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [ParallelOptions](../../paralleloptions/)
* Klass [Parallel](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)