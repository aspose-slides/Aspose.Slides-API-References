---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides för Java API-referens
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

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enumen CombinableSeriesTypesGroup. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i samma grupp). Således är principen för seriegruppering en gruppering efter de ovan nämnda typgrupperna samt efter primär/sekundär plottyp.
2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper"). "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv. Varje av "seriegruppsegenskaper" kan ha en endast läsbar projektion i klassen ChartSeries.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Hämtar seriegruppen efter serie. |
| [get_Item(int index)](#get-Item-int-) | Hämtar seriegruppen efter index. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Hämtar seriegruppen efter serie.

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

Hämtar seriegruppen efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)