---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje kolekci skupin kombinovatelných sérií.
type: docs
url: /cs/com.aspose.slides/ichartseriesgroupcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Reprezentuje kolekci skupin kombinovatelných sérií.

--------------------

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny kombinovatelných typů sérií jsou definovány a popsány pomocí enum CombinableSeriesTypesGroup. Také každá skupina sérií obsahuje sérii, která je vykreslena buď na primární ose, nebo na sekundární ose (ne v obou případech ve stejné skupině). Princip seskupování sérií je tedy seskupování podle výše zmíněných typových skupin a podle typu vykreslení – primární/sekundární. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině („vlastnosti skupiny sérií“). „Vlastnosti skupiny sérií“ v třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny sérií“ může mít jen pro čtení projekci v třídě ChartSeries.

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

**Návratová hodnota:**
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

**Návratová hodnota:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)