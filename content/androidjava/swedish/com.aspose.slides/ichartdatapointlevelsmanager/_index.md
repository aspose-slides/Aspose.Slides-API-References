---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides för Android via Java API-referens
description: Behållare för datapunktnivåer.
type: docs
url: /sv/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Behållare för datapunktnivåer. Används för Treeamp- och Sunburst-serier. Indexering av datapunktnivåer är nollbaserad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
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
public abstract int getCount()
```

Returnerar antalet datapunktnivåer.

**Returnerar:**
int