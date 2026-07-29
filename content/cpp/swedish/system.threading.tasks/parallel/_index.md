---
title: Parallel
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller stöd för parallella slingor och regioner.
type: docs
weight: 1
url: /sv/system.threading.tasks/parallel/
---
## Parallell klass

Tillhandahåller stöd för parallella slingor och regioner.

```cpp
class Parallel
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Utför en foreach-operation på ett IEnumerable där iterationer kan köras parallellt. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Utför en foreach-operation på ett IEnumerable där iterationer kan köras parallellt. |
## Anmärkningar

Denna klass tillhandahåller metoder för parallell exekvering av slingor och operationer.

## Se även

* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)