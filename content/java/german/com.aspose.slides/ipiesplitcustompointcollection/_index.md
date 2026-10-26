---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Punkten dar, die im zweiten Tortendiagramm- oder Balkenabschnitt eines Bar-of-Pie- oder Pie-of-Pie-Diagramms mit einer benutzerdefinierten Aufteilung gezeichnet werden.
type: docs
url: /de/com.aspose.slides/ipiesplitcustompointcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Stellt eine Sammlung von Punkten dar, die im zweiten Tortendiagramm- oder Balkenabschnitt eines Bar-of-Pie- oder Pie-of-Pie-Diagramms mit einer benutzerdefinierten Aufteilung gezeichnet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Diagrammdatenpunkt anhand des Index zurück. |
| [add(int dataPointIndex)](#add-int-) | Fügt den Datenpunkt anhand seines Indexes in der Punkte-Sammlung der übergeordneten Serie hinzu. |
| [remove(int dataPointIndex)](#remove-int-) | Entfernt das Element aus der Sammlung anhand seines Indexes in der Punkte-Sammlung der übergeordneten Serie. |
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

Fügt den Datenpunkt anhand seines Indexes in der Punkte-Sammlung der übergeordneten Serie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der Punkte-Sammlung der übergeordneten Serie. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Entfernt das Element aus der Sammlung anhand seines Indexes in der Punkte-Sammlung der übergeordneten Serie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | int | Index des Datenpunkts in der Punkte-Sammlung der übergeordneten Serie. |