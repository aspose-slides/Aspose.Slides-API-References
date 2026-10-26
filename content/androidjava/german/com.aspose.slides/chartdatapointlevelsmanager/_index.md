---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides für Android über Java API Referenz
description: Container für Datenpunkt-Ebenen.
type: docs
url: /de/com.aspose.slides/chartdatapointlevelsmanager/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Container für Datenpunkt-Ebenen. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indizierung der Datenpunkt-Ebenen ist nullbasiert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Gibt ein IChartDataPointLevel-Objekt für die definierte Ebene zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der Datenpunkt-Ebenen zurück. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Gibt ein IChartDataPointLevel-Objekt für die definierte Ebene zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| level | int |  |

**Rückgabe:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Datenpunkt-Ebenen zurück.

**Rückgabe:**
int