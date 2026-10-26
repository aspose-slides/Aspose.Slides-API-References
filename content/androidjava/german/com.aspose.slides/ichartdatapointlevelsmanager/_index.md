---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Container für Datenpunktebenen.
type: docs
url: /de/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Container für Datenpunktebenen. Angewendet für Treeamp- und Sunburst-Serien. Die Indizierung von Datenpunktebenen beginnt bei Null.
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
| Parameter | Typ | Beschreibung |
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