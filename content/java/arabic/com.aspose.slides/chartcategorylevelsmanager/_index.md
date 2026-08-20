---
title: ChartCategoryLevelsManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: حاوية مُدارة لقيم مستويات فئات المخطط.
type: docs
url: /ar/com.aspose.slides/chartcategorylevelsmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

حاوية مُدارة لقيم مستويات فئات المخطط.
## الطرق

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | يعيد كائن IChartDataCell للمستوى المحدد. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | يضبط عنصر التجميع للمستوى المحدد. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | يحذف عنصر التجميع للمستوى المحدد. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

يعيد كائن IChartDataCell للمستوى المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

يضبط عنصر التجميع للمستوى المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

يحذف عنصر التجميع للمستوى المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |