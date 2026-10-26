---
title: ForEach()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provede operaci foreach na IEnumerable, při které mohou být iterace prováděny paralelně.
type: docs
weight: 1
url: /cs/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Provede operaci foreach nad IEnumerable, při které mohou být iterace prováděny paralelně.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSource | Typ dat ve zdroji. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Zdroj dat, který lze enumerovat. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Objekt, který konfiguruje chování této operace. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegát, který je volán jednou na každou iteraci. |

### Návratová hodnota

Struktura [ParallelLoopResult](../../parallelloopresult/) obsahující informace o tom, jaká část smyčky byla dokončena.

## Poznámky



Tato metoda rozdělí zdrojový enumerovatelný objekt a souběžně spustí delegáta body na několika vláknech.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Provede operaci foreach nad IEnumerable, při které mohou být iterace prováděny paralelně.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TSource | Typ dat ve zdroji. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Zdroj dat, který lze enumerovat. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegát, který je volán jednou na každou iteraci. |

### Návratová hodnota

Struktura [ParallelLoopResult](../../parallelloopresult/) obsahující informace o tom, jaká část smyčky byla dokončena.

## Poznámky



Používá výchozí [ParallelOptions](../../paralleloptions/) s neomezeným paralelismem a bez zrušení.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Třída [ParallelLoopResult](../../parallelloopresult/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [ParallelOptions](../../paralleloptions/)
* Třída [Parallel](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)