---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Container of data point levels.
type: docs
url: /sv/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Behållare för datapunktnivåer. Tillämpas för Treeamp- och Sunburst-serier. Indexeringen av datapunktnivåer är nollbaserad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataPointLevel-objekt för definierad nivå. |
| [getCount()](#getCount--) | Returnerar antalet datapunktnivåer. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
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
public abstract int getCount()
```

Returnerar antalet datapunktnivåer.

**Returnerar:**
int