---
title: Parallel
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce supporto per cicli e regioni paralleli.
type: docs
weight: 1
url: /it/system.threading.tasks/parallel/
---
## Classe Parallel


Fornisce il supporto per cicli e regioni paralleli.

```cpp
class Parallel
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Esegue un'operazione foreach su un IEnumerable in cui le iterazioni possono essere eseguite in parallelo. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Esegue un'operazione foreach su un IEnumerable in cui le iterazioni possono essere eseguite in parallelo. |
## Osservazioni


Questa classe fornisce metodi per l'esecuzione parallela di cicli e operazioni. 
## Vedi anche

* Spazio dei nomi [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)