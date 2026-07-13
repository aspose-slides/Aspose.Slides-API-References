---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides för Android via Java API-referens
description: Hanterad behållare för värdena i diagrammets kategorinivåer.
type: docs
url: /sv/com.aspose.slides/chartcategorylevelsmanager/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

Hantera behållare för värdena i diagrammets kategorinivåer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataCell-objekt för angiven nivå. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Ställer in grupperingselement för angiven nivå. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Tar bort grupperingselement för angiven nivå. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```


Returnerar IChartDataCell-objekt för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```


Ställer in grupperingselement för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```


Tar bort grupperingselement för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |