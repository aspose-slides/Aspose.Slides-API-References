---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
weight: 686
url: /java/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Managed container of the values of the chart category levels.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Returns IChartDataCell object for defined level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Sets grouping item for defined level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Category level int |
| value | java.lang.Object | Groping item Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Delete grouping item for defined level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Category level int |

