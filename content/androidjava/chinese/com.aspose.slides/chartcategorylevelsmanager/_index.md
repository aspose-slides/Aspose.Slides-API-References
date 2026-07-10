---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API 参考
description: 用于管理图表类别级别值的容器。
type: docs
url: /zh/com.aspose.slides/chartcategorylevelsmanager/
---
**继承关系:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

管理图表类别级别值的容器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回为指定级别定义的 IChartDataCell 对象。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 为指定级别设置分组项。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 删除为指定级别定义的分组项。 |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

返回为指定级别定义的 IChartDataCell 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |

**返回值:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

为指定级别设置分组项。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

删除为指定级别定义的分组项。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |