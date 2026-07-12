---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Punkten dar, die im zweiten Kuchen- oder Balkendiagramm eines Bar-of-Pie bzw. Pie-of-Pie-Diagramms mit einer benutzerdefinierten Aufteilung gezeichnet werden sollen.
type: docs
url: /de/com.aspose.slides/ipiesplitcustompointcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Stellt eine Sammlung von Punkten dar, die im zweiten Kuchendiagramm- oder Balkendiagramm eines Bar-of-Pie- oder Pie-of-Pie-Diagramms mit einer benutzerdefinierten Aufteilung gezeichnet werden sollen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Diagrammdatenpunkt anhand des Index zurück. |
| [add(int dataPointIndex)](#add-int-) | Fügt einen Datenpunkt anhand seines Index in der Punktesammlung der übergeordneten Serie hinzu. |
| [remove(int dataPointIndex)](#remove-int-) | Entfernt ein Element aus der Sammlung anhand seines Index in der Punktesammlung der übergeordneten Serie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Gibt den Diagrammdatenpunkt anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Datenpunkts. |

**Rückgabe:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagrammdatenpunkt.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Fügt einen Datenpunkt anhand seines Index in der Punktesammlung der übergeordneten Serie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der Punktesammlung der übergeordneten Serie. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Entfernt ein Element aus der Sammlung anhand seines Index in der Punktesammlung der übergeordneten Serie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der Punktesammlung der übergeordneten Serie.. |