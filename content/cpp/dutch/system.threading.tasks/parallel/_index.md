---
title: Parallel
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt ondersteuning voor parallelle lussen en regio's.
type: docs
weight: 1
url: /nl/system.threading.tasks/parallel/
---
## Parallel klasse


Biedt ondersteuning voor parallelle lussen en regio's.

```cpp
class Parallel
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Voert een foreach-operatie uit op een IEnumerable waarbij iteraties parallel kunnen worden uitgevoerd. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Voert een foreach-operatie uit op een IEnumerable waarbij iteraties parallel kunnen worden uitgevoerd. |
## Opmerkingen


Deze klasse biedt methoden voor parallelle uitvoering van lussen en bewerkingen. 
## Zie ook

* Naamruimte [System::Threading::Tasks](../)
* Bibliotheek [Aspose.Slides](../../)