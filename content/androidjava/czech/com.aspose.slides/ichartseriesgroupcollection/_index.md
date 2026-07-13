---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje kolekci skupin kombinovatelných sérií.
type: docs
url: /cs/com.aspose.slides/ichartseriesgroupcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Představuje kolekci skupin kombinovatelných sérií.

--------------------

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny kombinovatelných typů sérií jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup. Také každá skupina sérií obsahuje sérii, která je vykreslena buď na primární ose, nebo na sekundární ose (nikoli obě případy v jedné skupině). Princip skupinování sérií je tedy seskupování podle výše uvedených typových skupin a podle typu vykreslení – primární či sekundární. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině („vlastnosti skupiny sérií“). „Series group properties“ ve třídě ChartSeriesGroup je read/write. Každá z „series group properties“ může mít v třídě ChartSeries read-only projekci.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Získá skupinu sérií podle série. |
| [get_Item(int index)](#get-Item-int-) | Získá skupinu sérií podle indexu. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Získá skupinu sérií podle série.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Vrací:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Získá skupinu sérií podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)