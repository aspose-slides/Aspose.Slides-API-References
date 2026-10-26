---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides Java API referencia
description: Adatszint szintek tárolója.
type: docs
url: /hu/com.aspose.slides/chartdatapointlevelsmanager/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Adatszint szintek tárolója. A Treeamp és Sunburst sorozatokhoz alkalmazható. Az adatszintszintek indexelése nullától kezdődik.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Visszaad egy IChartDataPointLevel objektumot a megadott szinthez. |
| [getCount()](#getCount--) | Visszaadja az adatpont szintek számát. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Visszaad egy IChartDataPointLevel objektumot a megadott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |

**Visszatérési érték:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja az adatpont szintek számát.

**Visszatérési érték:**
int