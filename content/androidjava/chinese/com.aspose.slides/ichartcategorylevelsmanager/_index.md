---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API 参考
description: 管理图表类别级别值的容器。
type: docs
url: /zh/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

管理图表类别级别值的容器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回为定义级别的 IChartDataCell 对象。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 设置定义级别的分组项。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 删除定义级别的分组项。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

返回为定义级别的 IChartDataCell 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

设置定义级别的分组项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int | 类别级别 int |
| value | java.lang.Object | 分组项对象 |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

删除定义级别的分组项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int | 类别级别 int |