---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides Java API 参考
description: 托管图表类别级别值的容器。
type: docs
url: /zh/com.aspose.slides/chartcategorylevelsmanager/
---
**继承:**
java.lang.Object

**实现的所有接口:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

管理图表类别级别的容器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回为指定级别的 IChartDataCell 对象。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 为指定级别设置分组项。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 删除指定级别的分组项。 |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```


返回为指定级别的 IChartDataCell 对象。

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


删除指定级别的分组项。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |