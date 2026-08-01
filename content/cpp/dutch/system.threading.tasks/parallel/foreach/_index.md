---
title: ForEach()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een foreach-bewerking uit op een IEnumerable waarbij iteraties parallel kunnen worden uitgevoerd.
type: docs
weight: 1
url: /nl/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) methode


Voert een foreach-bewerking uit op een IEnumerable waarbij iteraties parallel kunnen worden uitgevoerd.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TSource | Het type van de gegevens in de bron. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Een enumerable gegevensbron. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Een object dat het gedrag van deze bewerking configureert. |
| body | const [Action](../../../system/action/)\<TSource\>\& | De delegate die eenmaal per iteratie wordt aangeroepen. |

### Retourwaarde

Een [ParallelLoopResult](../../parallelloopresult/)-structuur die informatie bevat over welk deel van de lus is voltooid.

## Opmerkingen



Deze methode partitioneert de bron-enumerable en voert de body-delegate op meerdere threads gelijktijdig uit.
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) methode


Voert een foreach-bewerking uit op een IEnumerable waarbij iteraties parallel kunnen worden uitgevoerd.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TSource | Het type van de gegevens in de bron. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Een enumerable gegevensbron. |
| body | const [Action](../../../system/action/)\<TSource\>\& | De delegate die eenmaal per iteratie wordt aangeroepen. |

### Retourwaarde

Een [ParallelLoopResult](../../parallelloopresult/)-structuur die informatie bevat over welk deel van de lus is voltooid.

## Opmerkingen



Gebruikt standaard [ParallelOptions](../../paralleloptions/) met onbeperkte paralleliteit en zonder annulering. 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasse [ParallelLoopResult](../../parallelloopresult/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [ParallelOptions](../../paralleloptions/)
* Klasse [Parallel](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)