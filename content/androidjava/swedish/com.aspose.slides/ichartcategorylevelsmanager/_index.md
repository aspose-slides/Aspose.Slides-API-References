---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /sv/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Hanterad behållare för värdena i diagrammets kategorinivåer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataCell-objekt för definierad nivå. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Ställer in grupperingsobjekt för definierad nivå. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Tar bort grupperingsobjekt för definierad nivå. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Returnerar IChartDataCell-objekt för definierad nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Ställer in grupperingsobjekt för definierad nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int | Kategorinivå int |
| value | java.lang.Object | Grupperingsobjekt Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Tar bort grupperingsobjekt för definierad nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int | Kategorinivå int |