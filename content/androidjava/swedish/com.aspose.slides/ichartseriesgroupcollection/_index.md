---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar samlingen av grupper av kombinerbara serier.
type: docs
url: /sv/com.aspose.slides/ichartseriesgroupcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Representerar samlingen av grupper av kombinerbara serier.

--------------------

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med CombinableSeriesTypesGroup enum. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i en grupp). Så är principen för seriegroupering en gruppering efter de ovan nämnda typgrupperna och efter primär/sekundär plottyp. 2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i ChartSeriesGroup class är read/write. Varje av "series group properties" kan ha en read-only projection i ChartSeries class.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Hämtar serieggruppen via serie. |
| [get_Item(int index)](#get-Item-int-) | Hämtar serieggruppen via index. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Hämtar serieggruppen via serie.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

Hämtar serieggruppen via index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)