---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides لواجهة برمجة التطبيقات Java
description: حاوية مُدارة لقيم مستويات فئات المخطط.
type: docs
url: /ar/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

حاوية مُدارة لقيم مستويات فئات المخطط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | إرجاع كائن IChartDataCell للمستوى المحدد. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | تعيين عنصر التجميع للمستوى المحدد. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | حذف عنصر التجميع للمستوى المحدد. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

إرجاع كائن IChartDataCell للمستوى المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| level | int |  |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

تعيين عنصر التجميع للمستوى المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| level | int | مستوى الفئة int |
| value | java.lang.Object | كائن عنصر التجميع |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

حذف عنصر التجميع للمستوى المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| level | int | مستوى الفئة int |