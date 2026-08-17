---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Container of data point levels.
type: docs
url: /de/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Container für Datenpunktebenen. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indizierung der Datenpunktebenen ist nullbasiert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Gibt ein IChartDataPointLevel-Objekt für die angegebene Ebene zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der Datenpunktebenen zurück. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Gibt ein IChartDataPointLevel-Objekt für die angegebene Ebene zurück.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Rückgabewert:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der Datenpunktebenen zurück.

**Rückgabewert:**
int