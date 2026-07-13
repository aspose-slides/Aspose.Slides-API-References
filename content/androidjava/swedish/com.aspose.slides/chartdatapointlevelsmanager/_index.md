---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides för Android via Java API-referens
description: Behållare för datapoängsnivåer.
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

Behållare för datapoängsnivåer. Används för Treeamp och Sunburst-serier. Indexering av datapoängsnivåer är nollbaserad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataPointLevel-objekt för definierad nivå. |
| [getCount()](#getCount--) | Returnerar antalet datapoängsnivåer. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Returnerar IChartDataPointLevel-objekt för definierad nivå.

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


Returnerar antalet datapoängsnivåer.

**Returnerar:**
int