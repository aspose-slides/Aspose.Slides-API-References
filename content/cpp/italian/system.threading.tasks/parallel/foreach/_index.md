---
title: ForEach()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue un'operazione foreach su un IEnumerable in cui le iterazioni possono essere eseguite in parallelo.
type: docs
weight: 1
url: /it/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method

Esegue un'operazione foreach su un IEnumerable in cui le iterazioni possono essere eseguite in parallelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSource | Il tipo dei dati nella sorgente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Una fonte dati enumerabile. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Un oggetto che configura il comportamento di questa operazione. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Il delegato invocato una volta per iterazione. |

### Valore restituito

Una struttura [ParallelLoopResult](../../parallelloopresult/) che contiene informazioni sulla parte del ciclo completata.

## Osservazioni



Questo metodo partiziona la sorgente enumerabile ed esegue il delegato body su più thread contemporaneamente. 

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method

Esegue un'operazione foreach su un IEnumerable in cui le iterazioni possono essere eseguite in parallelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSource | Il tipo dei dati nella sorgente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Una fonte dati enumerabile. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Il delegato invocato una volta per iterazione. |

### Valore restituito

Una struttura [ParallelLoopResult](../../parallelloopresult/) che contiene informazioni sulla parte del ciclo completata.

## Osservazioni



Usa il [ParallelOptions](../../paralleloptions/) predefinito con parallelismo illimitato e nessuna cancellazione. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Classe [ParallelLoopResult](../../parallelloopresult/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [ParallelOptions](../../paralleloptions/)
* Classe [Parallel](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)