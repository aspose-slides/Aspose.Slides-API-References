---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Hantera behållare för värdena på diagrammets kategorinivåer.
type: docs
url: /sv/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Hantera behållare för värdena på diagrammets kategorinivåer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returnerar IChartDataCell-objekt för angiven nivå. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Ställer in grupperingselement för angiven nivå. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Tar bort grupperingselement för angiven nivå. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Returnerar IChartDataCell-objekt för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int |  |

**Returvärde:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Ställer in grupperingselement för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int | Kategorinivå int |
| value | java.lang.Object | Grupperingsobjekt |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Tar bort grupperingselement för angiven nivå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | int | Kategorinivå int |