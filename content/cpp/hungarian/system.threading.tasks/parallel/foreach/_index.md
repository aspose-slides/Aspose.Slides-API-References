---
title: ForEach()
second_title: Aspose.Slides a C++ API referenciája
description: Végrehajt egy foreach műveletet egy IEnumerable-en, amelyben az iterációk párhuzamosan futtathatók.
type: docs
weight: 1
url: /hu/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) metódus


Végrehajt egy foreach műveletet egy IEnumerable-en, amelyben a iterációk párhuzamosan futhatnak.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSource | A forrásban lévő adatok típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Egy felsorolható adatforrás. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Egy objektum, amely konfigurálja ennek a műveletnek a viselkedését. |
| body | const [Action](../../../system/action/)\<TSource\>\& | A delegált, amely minden iterációban egyszer meghívódik. |

### Visszatérési érték

Egy [ParallelLoopResult](../../parallelloopresult/) szerkezet, amely információt tartalmaz arról, hogy a kör teljesített része milyen mértékű volt.

## Megjegyzések



Ez a metódus felosztja a forrás enumerable-t, és a body delegáltat több szálon párhuzamosan hajtja végre.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) metódus


Végrehajt egy foreach műveletet egy IEnumerable-en, amelyben a iterációk párhuzamosan futhatnak.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TSource | A forrásban lévő adatok típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Egy felsorolható adatforrás. |
| body | const [Action](../../../system/action/)\<TSource\>\& | A delegált, amely minden iterációban egyszer meghívódik. |

### Visszatérési érték

Egy [ParallelLoopResult](../../parallelloopresult/) szerkezet, amely információt tartalmaz arról, hogy a kör teljesített része milyen mértékű volt.

## Megjegyzések



Alapértelmezett [ParallelOptions](../../paralleloptions/)-t használ korlátlan párhuzamossággal és megszakítás nélkül.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Osztály [ParallelLoopResult](../../parallelloopresult/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [ParallelOptions](../../paralleloptions/)
* Osztály [Parallel](../)
* Névtere [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)