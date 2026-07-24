---
title: Parallel
second_title: Aspose.Slides für C++ API-Referenz
description: Bietet Unterstützung für parallele Schleifen und Regionen.
type: docs
weight: 1
url: /de/system.threading.tasks/parallel/
---
## Parallelklasse

Bietet Unterstützung für parallele Schleifen und Regionen.

```cpp
class Parallel
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Führt eine foreach-Operation auf einem IEnumerable aus, bei der die Iterationen parallel ausgeführt werden können. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Führt eine foreach-Operation auf einem IEnumerable aus, bei der die Iterationen parallel ausgeführt werden können. |
## Bemerkungen

Diese Klasse stellt Methoden für die parallele Ausführung von Schleifen und Operationen bereit.

## Siehe auch

* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)