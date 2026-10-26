---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides för Java API-referens
description: Behållare för datapunktsnivåer.
type: docs
url: /sv/com.aspose.slides/chartdatapointlevelsmanager/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Behållare för datapunktsnivåer. Används för Treeamp- och Sunburst-serier. Indexering av datapunktsnivåer är nollbaserad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataPointLevel-objekt för angiven nivå. |
| [getCount()](#getCount--) | Returnerar antalet datapunktsnivåer. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Returnerar IChartDataPointLevel-objekt för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |

**Returnerar:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet datapunktsnivåer.

**Returnerar:**
int